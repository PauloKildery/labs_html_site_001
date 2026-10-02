# 🛍️ Shopping App — Front-End

Projeto desenvolvido como atividade prática de **Front-End**, utilizando como referência um layout disponibilizado no **Figma**.

O objetivo desta primeira etapa foi transformar o layout visual em uma página web utilizando **HTML5 e CSS3**, trabalhando estrutura semântica, estilização, organização de arquivos, responsividade, animações e interações visuais.

> **Status:** Aula 01 concluída — HTML e CSS.

---

## 🎯 Objetivo do projeto

Praticar os fundamentos do desenvolvimento Front-End através da construção de uma interface de e-commerce de moda.

Nesta primeira etapa foram trabalhados:

- Estruturação da página com HTML5;
- HTML semântico;
- Estilização com CSS3;
- Flexbox;
- CSS Grid;
- organização de imagens e assets;
- efeitos de `hover`;
- `transition` e `transform`;
- animações com `@keyframes`;
- responsividade com Media Queries;
- adaptação do layout para diferentes tamanhos de tela.

---

## 🎨 Referência visual

O projeto foi desenvolvido utilizando como referência um layout criado/disponibilizado no **Figma**.

O layout serviu como base visual para a implementação, mas alguns elementos foram adaptados durante o desenvolvimento para melhorar a apresentação e permitir a prática de recursos adicionais de CSS.

---

## 💻 Tecnologias utilizadas

### HTML5

Utilizado para estruturar semanticamente a página.

Principais elementos utilizados:

```html
<header>
<nav>
<main>
<section>
<div>
<h1>
<p>
<a>
<img>
```

### CSS3

Utilizado para toda a parte visual e responsiva da aplicação.

Foram utilizados recursos como:

```css
display: flex;
display: grid;
transition;
transform;
filter;
@keyframes;
@media;
```

### JavaScript

O arquivo:

```text
frontend/js/script.js
```

foi preparado na estrutura do projeto, porém **JavaScript ainda não foi utilizado nesta etapa**.

As funcionalidades JavaScript poderão ser implementadas nas próximas aulas.

---

## 📁 Estrutura do projeto

```text
labs_html_site_001/
│
├── backend/
│
├── docs/
│
├── frontend/
│   │
│   ├── assets/
│   │   ├── brands/
│   │   │   ├── amazon.svg
│   │   │   ├── hm.svg
│   │   │   ├── lacoste.svg
│   │   │   ├── levis.svg
│   │   │   ├── obey.svg
│   │   │   └── shopify.svg
│   │   │
│   │   ├── icons/
│   │   │
│   │   └── images/
│   │       └── hero-model.png
│   │
│   ├── css/
│   │   └── style.css
│   │
│   ├── js/
│   │   └── script.js
│   │
│   └── index.html
│
├── .gitignore
└── README.md
```

---

## 🧱 Componentes desenvolvidos

### Header

O cabeçalho possui:

- logotipo `FASHION`;
- menu de navegação;
- botão `SIGN UP`;
- efeito de linha amarela nos links durante o `hover`;
- animação no botão `SIGN UP`.

---

### Hero Section

A área principal contém:

- título de destaque;
- elementos gráficos brancos e amarelos;
- descrição da coleção;
- botão `SHOP NOW`;
- imagem principal da modelo;
- círculo amarelo decorativo;
- sombra aplicada à imagem;
- animação de entrada do texto;
- efeitos de `hover`.

---

## 🏷️ Brands Section

Foi criada uma seção para apresentação das marcas:

- H&M;
- OBEY;
- Shopify;
- Lacoste;
- Levi's;
- Amazon.

Os logos foram organizados dentro de:

```text
frontend/assets/brands/
```

A seção utiliza o amarelo como identidade visual e possui efeitos de destaque nos logos.

Ao passar o mouse sobre uma marca, o logo aumenta utilizando:

```css
transform: scale();
```

Também foi utilizado:

```css
filter: drop-shadow();
```

para criar profundidade visual.

---

## ✨ Animações e interações

Foram implementados diferentes efeitos utilizando somente CSS.

### Links do menu

Linha amarela animada utilizando:

```css
.nav-list a::after
```

### Botões

Os botões utilizam:

```css
transition
transform
box-shadow
```

para criar efeitos suaves durante a interação.

### Imagem principal

A imagem da Hero possui efeito de ampliação com:

```css
transform: scale();
```

### Entrada do conteúdo

Foi criada uma animação utilizando:

```css
@keyframes heroTextEntrada
```

---

## 📱 Responsividade

O projeto utiliza **Media Queries** para adaptar o layout a diferentes larguras de tela.

Foram criados breakpoints para:

```css
@media (max-width: 900px)
```

e:

```css
@media (max-width: 600px)
```

Durante o desenvolvimento, o layout foi testado manualmente através do **Chrome DevTools**.

Foram utilizados como pontos de validação:

| Tipo | Largura testada |
|---|---:|
| Mobile | 390px |
| Tablet | 768px |
| Desktop | 1440px |

No mobile:

- o menu tradicional é ocultado;
- Header é simplificado;
- Hero passa de duas colunas para uma coluna;
- texto é centralizado;
- imagem é posicionada abaixo do conteúdo;
- elementos decorativos são redimensionados;
- marcas são reorganizadas utilizando CSS Grid.

---

## 🧪 Testes realizados

Durante o desenvolvimento foram realizados testes utilizando:

- Live Server;
- Google Chrome;
- Chrome DevTools;
- Device Toolbar;
- inspeção de elementos;
- diferentes larguras de viewport.

O projeto foi validado visualmente nos tamanhos definidos durante esta primeira etapa.

---

## ▶️ Executando o projeto localmente

Clone o repositório:

```bash
git clone URL_DO_REPOSITORIO
```

Entre na pasta:

```bash
cd labs_html_site_001
```

Abra o projeto no VS Code:

```bash
code .
```

Depois abra:

```text
frontend/index.html
```

utilizando a extensão **Live Server**.

O endereço local poderá aparecer, por exemplo, como:

```text
http://127.0.0.1:5500/frontend/index.html
```

---

## 📝 Histórico de desenvolvimento

### Aula 01 — HTML + CSS

Nesta etapa foram estudados e aplicados:

- estrutura básica do HTML;
- HTML semântico;
- organização de diretórios;
- utilização de classes;
- containers;
- Flexbox;
- CSS Grid;
- imagens e caminhos relativos;
- estilização de botões;
- efeitos de hover;
- transitions;
- transforms;
- sombras;
- animações;
- pseudo-elementos;
- Media Queries;
- responsividade;
- testes utilizando Chrome DevTools.

---

## 🔧 Git e GitHub

O projeto será versionado utilizando **Git** e armazenado no **GitHub**.

Os comandos utilizados durante o versionamento serão documentados nesta seção conforme forem executados.

### Comandos

```bash
# Os comandos utilizados serão adicionados aqui
# na etapa de versionamento do projeto.
```

---

## 🚀 Deploy

O deploy público será realizado após o versionamento do projeto.

```text
URL do deploy: será adicionada após a publicação.
```

---

## 📚 Próximas etapas

O projeto poderá evoluir nas próximas aulas com:

- novas seções do layout;
- JavaScript;
- menu mobile;
- interações com o usuário;
- catálogo de produtos;
- favoritos;
- carrinho de compras;
- integração com API;
- Back-End;
- banco de dados;
- deploy e automação.

---

## 📌 Status do projeto

**Aula 01 — Front-End (HTML + CSS): concluída.**

O projeto continuará evoluindo conforme o conteúdo das próximas aulas.

---

## 🌐 Deploy

O projeto foi publicado utilizando o GitHub Pages.

🔗 **Acesse o projeto online:**  
https://paulokildery.github.io/labs_html_site_001/

🔗 **Repositório no GitHub:**  
https://github.com/PauloKildery/labs_html_site_001

---

## 📚 Tecnologias utilizadas

- HTML5
- CSS3
- Flexbox
- Media Queries
- SVG
- Git
- GitHub
- GitHub Pages
- Figma como referência visual

---

## 📱 Responsividade

O layout foi adaptado para diferentes tamanhos de tela utilizando Media Queries no CSS.

Foram realizados testes de responsividade através do Chrome DevTools, incluindo visualizações em:

- Desktop
- Tablet — aproximadamente 768px
- Mobile — aproximadamente 390px

---

## 🧠 Aprendizados da Aula 01

Durante o desenvolvimento deste projeto foram praticados:

- Estrutura semântica com HTML5;
- Organização e estilização com CSS3;
- Flexbox para posicionamento dos elementos;
- Uso de imagens PNG e logos em SVG;
- Efeitos de `hover`;
- Transições e animações CSS;
- Responsividade com Media Queries;
- Testes utilizando Chrome DevTools;
- Organização de arquivos e diretórios;
- Versionamento utilizando Git;
- Criação de repositório no GitHub;
- Publicação do projeto utilizando GitHub Pages.

> Nesta primeira etapa o projeto foi desenvolvido com foco em HTML5 e CSS3. JavaScript não foi implementado.

---

## 📝 Comandos Git praticados

```bash
git init
git status
git add .
git commit -m "feat: implementa layout responsivo da aula 01"
git log --oneline
git branch -M main
git remote -v
git push -u origin main
git mv
git rm
git push


### Depois de colar

Salve o `README.md` com **Ctrl + S**.

E, se você precisa entrar na aula **agora**, pode parar aí. O site já está publicado e o README ficará atualizado localmente.

Depois fazemos apenas:

```bash
git add README.md
git commit -m "docs: adiciona informações de deploy da aula 01"
git push

O projeto poderá receber novas funcionalidades nas próximas aulas conforme a evolução dos estudos.


