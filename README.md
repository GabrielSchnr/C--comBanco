Catálogo de Produtos com Favoritos

Este é um projeto em C# com Windows Forms que consome dados de uma API de produtos, permite filtrar os produtos por faixa de preço e categoria, armazenar os dados em um banco de dados SQL Server e gerenciar uma lista de favoritos.

Funcionalidades

- 🔄 Obter Produtos: Faz requisição para a API [FakeStoreAPI](https://fakestoreapi.com/products).
- 🔍 Filtrar Produtos:
- Por faixa de preço.
- Por categoria.
- 💾 Salvar produtos** no banco de dados (`tb_Produto`).
- ⭐ Adicionar aos favoritos** (armazenados em `tb_Favoritos`).
- 📋 Listar produtos favoritos**.

Tecnologias Utilizadas

- 💻 C# com Windows Forms
- 🗃️ SQL Server (com integração via System.Data.SqlClient)
- 🌐 Consumo de API com HttpClient
- 🧩 Organização em classes:
- Produto - representa o modelo de produto.
- Connection - lida com persistência em banco de dados.
- Form1 - interface gráfica principal do usuário.

Estrutura do Projeto

- Form1.cs               Interface e lógica de interação
- Connection.cs          Operações com banco de dados
- Produto.cs             Modelo de dados do produto
- Program.cs             Ponto de entrada da aplicação


