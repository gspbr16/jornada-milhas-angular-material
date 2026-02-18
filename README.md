Projeto desenvolvido com [Angular](https://angular.dev/) e [Angular Material](https://material.angular.io/) para simular uma plataforma de compartilhamento e venda de milhas aéreas.

## Funcionalidades

- Layout responsivo utilizando Angular Material.
- Banner ilustrativo e cabeçalho com navegação.
- Formulário para busca de passagens aéreas.
- Estilização customizada com SCSS.
- Testes unitários com Jasmine e Karma.

## Estrutura do Projeto

```
src/
  ├── app/
  │   ├── banner/
  │   ├── form-busca-passagens/
  │   ├── header/
  │   ├── app.component.ts
  │   ├── app.component.html
  │   ├── app.component.scss
  │   └── app.config.ts
  ├── index.html
  ├── main.ts
  ├── styles.scss
  ├── reset.scss
  └── _theme-colors.scss
public/
  └── images/
```

## Pré-requisitos

- [Node.js](https://nodejs.org/) (versão recomendada: 18+)
- [Angular CLI](https://angular.dev/tools/cli) (versão recomendada: 19+)

## Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/seu-usuario/jornada-milhas.git
cd jornada-milhas
npm install
```

## Como rodar o projeto

Para iniciar o servidor de desenvolvimento:

```bash
npm start
```

Acesse [http://localhost:4200](http://localhost:4200) no navegador.

## Como rodar os testes

Execute os testes unitários:

```bash
npm test
```

## Como gerar build de produção

```bash
npm run build
```

Os arquivos serão gerados na pasta `dist/jornada-milhas`.

## Personalização

- As cores do tema estão em [`src/_theme-colors.scss`](src/_theme-colors.scss).
- Os estilos globais estão em [`src/styles.scss`](src/styles.scss) e [`src/reset.scss`](src/reset.scss).
- Os componentes principais estão em [`src/app`](src/app).

## Estrutura dos Componentes

- [`HeaderComponent`](src/app/header/header.component.ts): Cabeçalho com navegação e botões.
- [`BannerComponent`](src/app/banner/banner.component.ts): Banner ilustrativo.
- [`FormBuscaPassagensComponent`](src/app/form-busca-passagens/form-busca-passagens.component.ts): Formulário de busca de passagens.
