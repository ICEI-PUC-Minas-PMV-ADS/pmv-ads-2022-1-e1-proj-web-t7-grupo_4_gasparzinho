# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

## Diagrama de componentes

Diagrama que permite a modelagem física de um sistema, através da visão dos seus componentes e relacionamentos entre os mesmos.

Exemplo: 


![image](https://user-images.githubusercontent.com/93995106/164831713-f74f31a5-d849-479e-8692-3aac2e1e97e6.jpg)
<br>

A solução implementada conta com os seguintes módulos:
- **Navegador** - Interface básica do sistema  
  - **Páginas Web** - Conjunto de arquivos HTML, CSS, JavaScript e imagens que implementam as funcionalidades do sistema.
   - **Local Storage** - armazenamento mantido no Navegador, onde são implementados bancos de dados baseados em JSON. São eles: 
     - **Canais** - seções de notícias apresentadas 
     - **Comentários** - registro de opiniões dos usuários sobre as notícias
     - **Preferidas** - lista de notícias mantidas para leitura e acesso posterior
 
 
 - **Hospedagem** - local na Internet onde as páginas são mantidas e acessadas pelo navegador.


A imagem anterior ilustra o processo do usuário em nossa solução. Assim
que o usuário entra no site, é apresentado à ele uma tela (Tela 1) para que ele possa realizar seu pedido.
Ao clicar no botão "Faça seu pedido" será aberto uma tela de cadastro (Tela 2).

Após realizar o cadastro, o cliente será encaminhado (Tela 3) para o menu 
principal onde será apresentado o cardápio da hamburgueria, com as seguintes informações: Entradas, Hambúrgeres,
Molhos, Bebidas, Acréscimos e sobremesas.

Ao escolher seu pedido, aparecerá ao lado da tela a opçao de finalizar o pedido e a escolha da forma de pagamento.


## Tecnologias Utilizadas

As tecnologias utilizadas para essa aplicação web foram, HTML (marcação), CSS (Estilização) e JavaScript (linguagem de programação).
O banco de dados utilizado foi MySQL Server.


## Hospedagem

Hospedagem do site será utilizado o Hostinger.

https://www.hostinger.com.br/hospedagem-de-sites
