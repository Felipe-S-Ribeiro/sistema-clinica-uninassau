Criadores:
Felipe Ribeiro
Vitor Hugor Viana
Rafael Bom Conselho
Everton Santos
Renan Faleta


Sistema de Gestão | Clínica Escola Uninassau
Este projeto é um sistema web de gestão desenvolvido para a Clínica Escola Uninassau. A aplicação permite o controle de vendas e produtos, oferecendo uma interface simples para registrar transações e visualizar relatórios detalhados.

 Funcionalidades:
- Cadastro de Produtos: Interface para adicionar e gerenciar os produtos.
- Registro de Vendas: Formulário dinâmico para registrar vendas com múltiplos itens e vendedores.
- Relatório Detalhado: Visualização de todas as vendas realizadas, com indicadores de performance (KPIs) como faturamento total e total de vendas.
- Filtros Avançados: Capacidade de filtrar o relatório de vendas por período (data inicial e final) e por vendedor.
- Impressão de Recibos: Geração de um recibo formatado para cada venda individual.
-Exportação para Excel: Funcionalidade para exportar o relatório de vendas visível para um arquivo .xlsx.



 Tecnologias Utilizadas:

Tecnologia	Motivo da Escolha
Node.js	Ambiente de execução do JavaScript no backend. Permite construir um servidor rápido e escalável, utilizando uma única linguagem (JavaScript) em todo o projeto.
Express.js	Framework minimalista para Node.js. Foi utilizado para criar o servidor web, gerenciar as rotas da aplicação (ex: /vendas, /produtos) e manipular as requisições HTTP de forma simples e organizada.
Nunjucks	Template Engine para o frontend. Foi escolhida por sua sintaxe simples e poderosa (similar a outras engines), permitindo criar páginas HTML dinâmicas ao injetar dados vindos do servidor.
MongoDB	Banco de dados NoSQL orientado a documentos. Ideal para este projeto por sua flexibilidade, facilitando o armazenamento de dados com estruturas variadas, como uma venda com uma lista de produtos.
MongoDB Compass	Ferramenta de interface gráfica (GUI) utilizada para visualizar, consultar e gerenciar os dados diretamente no banco de dados MongoDB de forma intuitiva.
JavaScript (Puro)	Utilizado no lado do cliente (navegador) para adicionar interatividade à página sem a necessidade de um framework pesado, como a adição dinâmica de produtos no formulário de venda.
Yarn	Gerenciador de pacotes. Foi usado no lugar do NPM para instalar e gerenciar as dependências do projeto (Express, Nunjucks, etc.), conhecido por sua performance e estabilidade.



Instalação e Execução
1 - Clone o Repositório

2 - Abra seu terminal (Bash, Git Bash, etc.) e clone o projeto do GitHub:
git clone https://github.com/seu-usuario/nome-do-repositorio.git

3 - Acesse a Pasta do Projeto
cd nome-do-repositorio

4 - Instale as Dependências

5 - Rode o comando yarn. Ele vai ler o arquivo package.json e baixar todas as bibliotecas necessárias (como Express e Nunjucks) para uma pasta chamada node_modules, preparando o projeto para ser executado.
yarn

6 - Configure as Variáveis de Ambiente

7 - Crie um arquivo chamado .env na raiz do projeto.

8 - Dentro dele, adicione a linha para conectar ao seu banco de dados local:
MONGODB_URI=mongodb://localhost:27017/sistema

9 - Inicie o Servidor
Rode o comando yarn dev

10 - Acesse a Aplicação

Abra seu navegador e acesse o endereço abaixo:

http://localhost:3002

