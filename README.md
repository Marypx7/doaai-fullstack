# 💜 DoaAí | Plataforma de Doações e Trocas Comunitárias

O DoaAí é um projeto de plataforma web voltada para doações e trocas de itens entre pessoas da mesma comunidade.

A ideia surgiu a partir da observação do descarte de objetos que ainda poderiam ser utilizados por outras pessoas. A proposta é desenvolver um sistema que facilite a publicação e a busca por esses itens, incentivando a reutilização e reduzindo o descarte desnecessário.

O projeto está em fase de desenvolvimento, começando pelo planejamento das interfaces e funcionalidades no Figma, seguido pela implementação do Front-end, Back-end e integração com banco de dados.

## Sobre o projeto

A plataforma permitirá que usuários publiquem itens disponíveis para doação, consultem produtos cadastrados e gerenciem suas próprias publicações.

O sistema também contará com recursos de autenticação, gerenciamento de perfil e acompanhamento das doações.

A proposta é construir uma aplicação que reúna diferentes funcionalidades em um único ambiente, trabalhando tanto a experiência do usuário quanto a estrutura e o funcionamento do sistema.

## UX/UI Design

O planejamento das interfaces foi realizado no Figma, onde desenvolvi os wireframes e organizei os principais fluxos de navegação.

Nessa etapa, foram definidos:

- Estrutura das páginas e organização das informações;
- Fluxos de cadastro, login e recuperação de senha;
- Navegação pelo catálogo de doações;
- Visualização dos detalhes de cada produto;
- Formulário para publicação de itens;
- Gerenciamento de anúncios e doações;
- Estrutura da área de perfil do usuário;
- Fluxo de denúncia e remoção de publicações.

### Wireframe

> <img width="15885" height="9504" alt="Mariana Pacini&#39;s team library" src="https://github.com/user-attachments/assets/2df3edbd-c5cd-4c00-a5ac-c63c8dc80a50" />
>

O wireframe apresenta a estrutura inicial das telas e a organização das funcionalidades previstas para a aplicação.

As interfaces poderão passar por ajustes durante o desenvolvimento, conforme a implementação e os testes das funcionalidades.

## Funcionalidades previstas

### Autenticação
- Cadastro de usuários;
- Login com e-mail e senha;
- Recuperação de senha;
- Gerenciamento de sessão;
- Logout.

### Publicações
- Cadastro de itens para doação;
- Upload de imagens;
- Informações e descrição dos produtos;
- Organização por categorias;
- Edição e exclusão de publicações;
- Gerenciamento do status dos anúncios.

### Catálogo
- Listagem dos produtos disponíveis;
- Busca por itens;
- Filtros por categoria;
- Página de detalhes dos produtos.

### Perfil do usuário
- Visualização e edição de dados;
- Gerenciamento das publicações;
- Histórico de doações;
- Acompanhamento dos itens cadastrados.

### Moderação
- Denúncia de publicações;
- Identificação do motivo da denúncia;
- Envio de informações para análise.

## Tecnologias

Tecnologias previstas para o desenvolvimento do projeto:

**Front-end**
- HTML5
- CSS3
- JavaScript

**Back-end**
- Node.js
- Express.js
- API REST

**Banco de dados**
- MongoDB

**Design e ferramentas**
- Figma
- Visual Studio Code
- Git e GitHub

A definição das tecnologias poderá ser ajustada conforme o desenvolvimento da aplicação.

## Estrutura do sistema

A aplicação será desenvolvida com separação entre Front-end, Back-end e banco de dados.

O Front-end será responsável pelas interfaces e interações do usuário, enquanto o Back-end ficará responsável pelas regras de negócio, autenticação e processamento das requisições.

A comunicação entre as camadas será realizada por meio de uma API REST, com persistência dos dados no banco de dados.

### Arquitetura prevista

```text
Front-end
HTML | CSS | JavaScript
          |
          v
       API REST
          |
          v
Back-end
Node.js | Express.js
          |
          v
Banco de Dados
MongoDB
```

## Desenvolvimento

O projeto será desenvolvido por etapas, começando pela estruturação das interfaces e avançando para a implementação das funcionalidades.

### Planejamento e Design
- [x] Definição da proposta do projeto
- [x] Levantamento inicial das funcionalidades
- [x] Desenvolvimento dos wireframes no Figma
- [x] Planejamento dos fluxos de navegação
- [ ] Refinamento das interfaces
- [ ] Finalização do protótipo

### Front-end
- [ ] Estruturação do projeto
- [ ] Desenvolvimento da página inicial
- [ ] Desenvolvimento do catálogo
- [ ] Página de detalhes dos produtos
- [ ] Interfaces de login e cadastro
- [ ] Formulário de publicação
- [ ] Área de perfil do usuário
- [ ] Responsividade das interfaces

### Back-end
- [ ] Configuração do Node.js e Express
- [ ] Estruturação das rotas
- [ ] Implementação da autenticação
- [ ] Cadastro e gerenciamento de usuários
- [ ] CRUD de produtos
- [ ] Validação de dados
- [ ] Tratamento de erros

### Banco de Dados
- [ ] Configuração do MongoDB
- [ ] Modelagem dos dados
- [ ] Integração com o Back-end
- [ ] Persistência de usuários e publicações

### Integração e Testes
- [ ] Integração entre Front-end e Back-end
- [ ] Testes das rotas da API
- [ ] Testes de autenticação
- [ ] Testes das operações CRUD
- [ ] Validação dos formulários
- [ ] Testes de responsividade
- [ ] Correções e ajustes

## Objetivo de aprendizado

Estou desenvolvendo o DoaAí para colocar em prática os conhecimentos adquiridos durante minha formação em Análise e Desenvolvimento de Sistemas.

O projeto envolve desde o planejamento das interfaces até a construção de uma aplicação com autenticação, gerenciamento de dados e comunicação entre Front-end e Back-end.

Durante o desenvolvimento, pretendo aprofundar meus conhecimentos em JavaScript, Node.js, Express, APIs REST e banco de dados, além de trabalhar a organização do código, versionamento e testes.

## Status

**Em desenvolvimento.**

O repositório será atualizado conforme as funcionalidades forem implementadas.

## Autora

**Mariana Pacini**

Estudante de Análise e Desenvolvimento de Sistemas.

- [GitHub](https://github.com/Marypx7)
- [LinkedIn](https://www.linkedin.com/in/mariana-pacini-07345720b/)
