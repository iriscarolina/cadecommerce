# README do Projeto de Carrinho de Compras

## Visão Geral

Este projeto é uma aplicação web básica para gerenciamento de um carrinho de compras. Inclui páginas para visualizar produtos, gerenciar categorias e marcas, e revisar pedidos. A aplicação utiliza PHP para a lógica do servidor, HTML para a estrutura das páginas e CSS para a estilização.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos principais:

### 1. Carrinho de Compras
- **`carrinho.php`**: Página que exibe os itens no carrinho e permite a gestão de produtos.

### 2. Cadastro e Gerenciamento
- **`cadastro-categoria.php`**: Página para cadastrar novas categorias de produtos.
- **`cadastro-marca.php`**: Página para cadastrar novas marcas de produtos.
- **`cadastro-produto.php`**: Página para cadastrar novos produtos com informações como nome, descrição, estoque, preço, categoria e marca.

### 3. Resumo do Pedido
- **`resumo-pedido.php`**: Página que exibe um resumo dos pedidos realizados.

## Estrutura dos Arquivos

### HTML e PHP

Cada página HTML inclui a estrutura básica e, quando necessário, integra código PHP para interagir com o banco de dados:

- **Cabeçalho**:
  - Inclui links para arquivos CSS e JS.
  - Exibe o título da página e links de navegação.

- **Corpo**:
  - Cada página contém um `<header>` para a navegação e um `<section>` para o conteúdo principal.
  - Utiliza PHP para carregar conteúdos dinâmicos e gerenciar a lógica de backend.

### CSS e JavaScript

- **CSS**:
- **JavaScript**:
- 
### Banco de Dados

- **Conexão com o Banco de Dados**:
  - Arquivo PHP **`controller/conexao.php`** para estabelecer a conexão com o banco de dados.

- **Consultas SQL**:
  - Consultas SQL são usadas para buscar e manipular dados de categorias, marcas e produtos.

## Instruções de Uso

1. **Configuração do Ambiente**:
   - Certifique-se de ter um servidor local configurado (como XAMPP ou WAMP) que suporte PHP e MySQL.
   - Configure o banco de dados conforme necessário e atualize as credenciais no arquivo **`conexao.php`**.

2. **Execução**:
   - Coloque todos os arquivos em um diretório acessível pelo servidor local.
   - Acesse a aplicação via navegador através da URL fornecida pelo servidor local (ex: `http://localhost/projeto`).

3. **Navegação**:
   - Use o link "Inicial" para retornar à página principal.
   - Navegue pelas páginas de cadastro e gerenciamento conforme necessário.

