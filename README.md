# Controle-de-Estoque-de-Pe-as
CADBIKE — Sistema Cadastro de Peças de Bicicletas

O CADBIKE é um sistema web desenvolvido para auxiliar no cadastro e gerenciamento de produtos e peças de uma bicicletaria. O projeto permite cadastrar códigos de produtos, registrar informações sobre peças e visualizar, alterar ou excluir produtos cadastrados.
O sistema foi desenvolvido com foco em uma interface simples e intuitiva, utilizando tecnologias web básicas e o LocalStorage do navegador para armazenamento dos dados.

**Funcionalidades**

Tela de login:

  * Acesso ao sistema por usuário e senha.
  * Validação das credenciais.

Cadastro de produtos:

  * Nome do produto.
  * Categoria.
  * Quantidade disponível.
  * Código do produto.
  * Valor do produto.

Cadastro de códigos:

  * Permite cadastrar códigos para os produtos.
  * Verificação de códigos cadastrados.

Visualização de produtos:

  * Lista de produtos cadastrados.
  * Exibição de categoria, código, quantidade e valor.
  * Alteração da quantidade.
  * Alteração do valor.
  * Exclusão de produtos.

Visualização de códigos:

  * Lista dos códigos cadastrados.
  * Identificação do produto relacionado ao código.
  * Indicação de códigos ainda não vinculados a produtos.

Tecnologias utilizadas:

O projeto foi desenvolvido utilizando:

HTML5 — estrutura das páginas;
CSS3 — estilização e layout;
JavaScript — lógica e funcionalidades do sistema;
LocalStorage — armazenamento dos códigos e produtos diretamente no navegador.

Estrutura do projeto:
CADBIKE/
│
└── bicicletaria/
    ├── index.html
    ├── dashboard.html
    ├── cadastrar-codigo.html
    ├── cadastrar-produto.html
    ├── ver-codigos.html
    ├── ver-produtos.html
    ├── script.js
    ├── style.css
    └── logo.png


Como executar o projeto:

1. Faça o download ou clone este repositório:

git clone https://github.com/seu-usuario/CADBIKE.git

2. Entre na pasta do projeto:
   
cd CADBIKE

4. Abra o arquivo:

bicicletaria/index.html


4. O sistema pode ser executado diretamente no navegador, sem necessidade de instalar um servidor ou banco de dados.

Acesso ao sistema:
Para fins de demonstração, o projeto possui um usuário padrão configurado no JavaScript.
Usuário: KamilaMarcon
Senha: 1234
Essas credenciais são apenas para demonstração. Em uma aplicação real, o sistema deveria utilizar autenticação segura e um banco de dados.

Armazenamento
O CADBIKE utiliza o LocalStorage, recurso disponível nos navegadores, para armazenar os dados cadastrados.

São armazenados principalmente:

* Códigos dos produtos;
* Produtos cadastrados;
* Quantidades;
* Valores;
* Categorias.

Como os dados ficam armazenados no navegador, eles não representam um banco de dados centralizado e podem ser diferentes em cada dispositivo ou navegador.

Objetivo do projeto

O principal objetivo do CADBIKE é desenvolver uma solução simples para facilitar o controle e organização de produtos e peças de uma bicicletaria, permitindo que o usuário tenha acesso rápido às informações cadastradas.

Além disso, o projeto proporciona a aplicação prática de conceitos de desenvolvimento web, JavaScript, manipulação do DOM e armazenamento de dados no navegador

Aprendizados
Durante o desenvolvimento do projeto, foram trabalhados conhecimentos como:

Estruturação de páginas com HTML;
Estilização utilizando CSS;
Programação em JavaScript;
Manipulação de elementos HTML através do DOM;
Criação de funções e validações;
Uso de `localStorage`;
Manipulação de arrays e objetos;
Criação de interfaces para cadastro e consulta de informações.

Melhorias
Algumas funcionalidades que podem ser implementadas em versões futuras:

Banco de dados real;
Sistema de cadastro de usuários;
Autenticação mais segura;
Pesquisa e filtros de produtos;
Controle de estoque;
Relatórios de produtos;
Histórico de alterações;
Interface responsiva para celulares;
Integração com um backend;
Deploy do sistema em uma plataforma web.

Desenvolvedora
Projeto desenvolvido por Kamila Marcon como projeto acadêmico/prático de desenvolvimento de sistemas.
