# SpendSmart - Expenses MVC

Projeto em ASP.NET Core MVC desenvolvido em .NET 8 para gerenciar despesas através do cadastro de produtos e seus respectivos preços. O projeto permite adicionar produtos, visualizar seus preços e calcular o valor total das despesas.

### Funcionalidades
- Cadastro de Produtos: Adicione produtos com nome e preço.
- Visualização de Produtos: Veja a lista de produtos cadastrados com seus preços.
- Cálculo do Valor Final: Calcule o total dos preços dos produtos adicionados.
- Interface Amigável: Interface simples e responsiva utilizando o padrão MVC.

### Tecnologias Utilizadas
- .NET 8: Framework principal para desenvolvimento.
- ASP.NET Core MVC: Estrutura para organizar as camadas de Model-View-Controller.
- Entity Framework Core: Para o gerenciamento de dados.
- In Memory: Banco de dados para armazenamento de produtos e preços, em tempo de excução.

### Estrutura do Projeto
- `Controllers`: Responsáveis por gerenciar as requisições e respostas do sistema.
    - ProductController: Controla as operações de produtos (adicionar, listar, remover).

- `Models`: Contêm as classes de domínio do projeto.
    - Product: Representa o produto com propriedades como Name e Price.

- `Views`: Interface para o usuário interagir com o sistema.
    - Product/Index: Exibe a lista de produtos e o valor final.
    - Product/Create: Formulário para adicionar novos produtos.

### Pacotes
    "Microsoft.EntityFrameworkCore" Version="8.0.10" 
    "Microsoft.EntityFrameworkCore.InMemory" Version="8.0.10"