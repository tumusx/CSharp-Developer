## C# - Developer 

Parabéns, você passou para a segunda fase do processo seletivo da MáximaTech para desenvolvedor Fullstack (C# + Angular).

## Instruções

1. Criar um fork deste repositório, transformar ele em privado, adicionar o nosso usuário (talentosmaxima) como colaborador e implementar o aplicativo conforme instruções abaixo.
2. Enviar um e-mail para <talentoshumanos@maximatech.com.br> com:
	* Assunto "[Teste Desenvolvedor C#] - Nome do candidato"
	* Link: -> Repositório privado no Github.

É hora do show!

## Resumo

Você foi escolhido para escrever uma PoC (Prova de Conceito) de um e-commerce, basicamente o sistema consiste na criação de Pedidos (cliente + produtos + frete).

O usuário após logar no sistema selecionará a opção "Novo Pedido" para iniciar a venda. 

## Seguem os requisitos:

* A stack de tecnologia a ser utilizada é C# .NET Core + Angular 6 ou Superior.
* O sistema é composto por 3 microserviços: Serviço Web (Angular) + API Backend (.NET Core) + Serviço de Cálculo de Frete (.NET Core).
* Banco de dados - NoSQL (MongoDB) ou SQL (PostgreSQL)
* Tela de listagem dos pedidos
* Todas as informações (JSONs e Pedidos) precisam ser persistidos no banco de dados escolhido.
* Documento descrevendo o processo de instalação do sistema
* O fluxo de autenticação é opcional, o mesmo poderá ser mockado para andamento do projeto.
* O Sistema deverá implementar o fluxo baseado nos arquivos de Design listados no item **Arquivos**

## Microserviço de Cálculo de Frete
O microserviço de cálculo de frete terá um webservice que  receberá a quantidade de itens que foram selecionados e multiplicará por um valor aleatório entre R$5,00 e R$10,00. Retornando assim o valor calculado.

### Exemplo
Foram selecionados 2 itens do Produto A e 1 item do Produto B, logo teremos 3 itens. O valor sorteado foi R$ 8,00. Assim: 3 x R$ 8,00 = R$ 24,00.

## Diferenciais

* Utilização de docker
* Load Balancer
* Utilização do Service Discovery e Api Gateway
* DDD e/ou CQRS
* Desenho Arquitetural
* Escrita de testes

## Arquivos

**GET Request -> Dados do Cliente e Produtos**

	Clientes: http://maximatech.free.beeceptor.com/cliente
	Produtos: http://maximatech.free.beeceptor.com/produto
  
**Design Mockup**

	URL : https://bit.ly/2P0cw5l
  
**Arquivos de Design**

	URL : https://go.aws/2uvDgkY	

## Design Preview

![Preview](https://uploaddeimagens.com.br/images/002/269/261/original/3-novo-pedido.png?1565958536)

## Critérios de Avaliação

* Organização do projeto
* Utilização de padrões arquiteturais
* Clareza do código
* Escolha de estruturas e bibliotecas
* Ausência de crashs e bugs
* Detalhes de UI
* Linguagem de programação

## Dúvidas
Entre em contato com talentoshumanos@maximatech.com.br
