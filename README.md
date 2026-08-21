# Mundo Disney — Integração com API

## Autor

* **Nome:** Eduardo da silva santos 
* **Ano:** 2026

## 1. Identificação do projeto

* **Nome do projeto:**Missao 117 
* **Instituição de ensino:** Unidade de Educação Profissional do Senac em Vila Velha.
* **Unidade curricular:** UC8 - Desenvolver Aplicações Mobile
* **Professor(a):**  Rafaela 

---

## 2. Sobre o projeto

>O projeto Mundo Disney é uma aplicação web que apresenta personagens da Disney de forma organizada e visual. As informações dos personagens são carregadas através de uma API, permitindo que os dados sejam obtidos de forma dinâmica.
>A aplicação possui cards com informações e imagens dos personagens e utiliza JavaScript para realizar a comunicação com a API e exibir os dados na página.

## 3. Estrutura do projeto

Apresente a organização dos arquivos e pastas do seu projeto.

Missao-117/ 
│ ├── index.html 
├── style.css 
├── script.js 
└── README.md

### Descrição dos arquivos

| Arquivo      | Descrição                                                        |
| ------------ | ---------------------------------------------------------------- |
| `index.html` |  Estrutura principal da página e dos elementos que serão exibidos.|                                                              |
| `style.css`  |  Responsável pelo visual da página, organização dos cards e layout.|                                                              |
| `script.js`  |  Responsável pela integração com a API, carregamento dos personagens e interação com a página.                                                             
| `README.md`  | Contém a documentação e as informações sobre o projeto. |                                                                |
| 
> **Caso seu projeto possua outras pastas ou arquivos, apresente-os também na estrutura acima.**

---

## 💻 4. Tecnologias utilizadas

Liste as tecnologias utilizadas no desenvolvimento do projeto.

HTML
CSS
JavaScript
API REST
Fetch API
CSS Grid
Visual Studio Code
---

## 5. API utilizada

### Nome da API

**Disney API**

### Endpoint utilizado

```text
https://api.disneyapi.dev/character
```

### Para que a API foi utilizada?

> A API foi utilizada para buscar informações dos personagens da Disney e exibir esses dados automaticamente na aplicação.

### Quais informações foram consumidas?

> Os principais dados utilizados foram:

Nome do personagem
Imagem do personagem
ID do personagem
Outras informações disponibilizadas pela API



##  6. Como executar o projeto



### Pré-requisitos

Para executar o projeto, é necessário ter um navegador atualizado, como Google Chrome, Microsoft Edge ou Mozilla Firefox.

Também é recomendado utilizar o Visual Studio Code para abrir e editar os arquivos do projeto.

### Passo a passo

*Baixe ou copie a pasta do projeto para o computador.
*Abra a pasta do projeto no Visual Studio Code.
*Verifique se os arquivos index.html, style.css e script.js estão na pasta correta.
*Abra o arquivo index.html no navegador.
*A aplicação será carregada e o JavaScript fará a comunicação com a API para buscar os personagens.
---

## 7. Como funciona a integração

Explique de forma objetiva e em até 10 passos como sua aplicação se comunica com a API.

1- O usuário abre a página index.html.
2- O navegador carrega os arquivos HTML, CSS e JavaScript.
3- O JavaScript identifica o local onde os personagens serão exibidos.
4- A aplicação realiza uma requisição para o endpoint da Disney API.
5- A API recebe a requisição.
6- A API retorna os dados dos personagens em formato JSON.
7- O JavaScript interpreta os dados recebidos.
8- Os personagens são criados dinamicamente em formato de cards.
9- As informações e imagens são inseridas nos cards.
10-Os cards são exibidos na página para o usuário.


## 8. Desafios encontrados

Registre pelo menos um problema ou dificuldade que você encontrou durante o desenvolvimento e como resolveu

### Desafio encontrado

**Problema:**

> [Descreva o problema encontrado.]

**Um dos problemas encontrados durante o desenvolvimento foi fazer os personagens aparecerem corretamente na página. Em alguns momentos, a aplicação não apresentava os dados porque havia erros na URL da API e no código JavaScript.**

> [Identifiquei o problema verificando o código JavaScript e observando o console do navegador. Também percebi que a URL utilizada para acessar a API estava escrita de forma incorreta.]


**Como resolvi:**

> [Corrigi o endereço do endpoint da API e organizei o código JavaScript responsável pela requisição. Também conferi os IDs dos elementos HTML para garantir que o JavaScript conseguisse encontrar corretamente os elementos da página.]

---

## 9. Aprendizados

> [Durante o desenvolvimento deste projeto, aprendi melhor como funciona a integração entre uma aplicação e uma API. Aprendi a utilizar o JavaScript para fazer requisições, receber dados em formato JSON e mostrar essas informações na página.

>Também aprendi a trabalhar melhor com HTML e CSS para criar os cards dos personagens e organizar o conteúdo utilizando CSS Grid. Além disso, aprendi que é importante verificar o console do navegador quando alguma parte do código não funciona, pois ele ajuda a encontrar os erros.

>Esse projeto também me ajudou a entender melhor como dados externos podem ser utilizados em uma aplicação para deixá-la mais dinâmica e interativa.]

---

---