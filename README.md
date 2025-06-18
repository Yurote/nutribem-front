# nutribem-front 🥗✨

-----

Bem-vindo ao **nutribem-front**\! Este é o aplicativo web dedicado a nutricionistas, desenvolvido para otimizar e simplificar a gestão de pacientes e planos alimentares.

## Descrição do Projeto

O **nutribem-front** é a interface de usuário construída com **React.js** para a plataforma NutriBem. Ele foi projetado especificamente para atender às necessidades de nutricionistas, oferecendo ferramentas intuitivas para gerenciar consultas, dietas personalizadas e acompanhamento do progresso dos pacientes. Nosso objetivo é proporcionar uma experiência fluida e eficiente para que você possa focar no que faz de melhor: cuidar da saúde dos seus pacientes.

## Build Setup

Para colocar o projeto `nutribem-front` em funcionamento na sua máquina, siga os passos abaixo:

### Pré-requisitos

Garanta que você tem o **Node.js** e o **npm** (Node Package Manager) instalados. Você pode verificar suas versões com:

```bash
node -v
npm -v
```

Se precisar instalá-los, visite o [site oficial do Node.js](https://nodejs.org/).

### Instalação

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/SeuUsuario/nutribem-front.git
    cd nutribem-front
    ```

2.  **Instale as dependências:**

    ```bash
    npm install
    ```

### Comandos de Desenvolvimento

Após a instalação, use estes comandos para interagir com o projeto:

  * **`npm start`**:
    Inicia o servidor de desenvolvimento. O aplicativo abrirá no seu navegador padrão (geralmente `http://localhost:3000`). Ele recarrega automaticamente quando você faz alterações e mostra erros de lint no console.

  * **`npm run build`**:
    Cria a versão de produção do aplicativo na pasta `build`. Este comando otimiza o código para o melhor desempenho, minifica o bundle e está pronto para implantação em um servidor.

  * **`npm test`**:
    Executa os testes da aplicação em modo interativo de observação. Para mais detalhes sobre testes, consulte a documentação do React.

  * **`npm run eject`**:
    **Atenção: Esta operação é irreversível\!**
    Se precisar de controle total sobre as configurações internas do Webpack, Babel e ESLint, você pode "ejetar" o projeto. Isso copiará todos os arquivos de configuração para o seu projeto, permitindo modificações diretas. Uma vez ejetado, não há como voltar atrás.

## Estrutura de Diretórios

O projeto `nutribem-front` segue a estrutura padrão gerada pelo `create-react-app`, facilitando a organização e manutenção do código:

```
nutribem-front/
├── node_modules/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── manifest.json
├── src/
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   └── reportWebVitals.js
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

-----

### `node_modules/`

Esta pasta contém todas as bibliotecas e pacotes JavaScript dos quais seu projeto depende. Eles são instalados via `npm install` com base no `package.json`. Você não deve editar arquivos aqui, e este diretório é ignorado pelo Git.

### `public/`

Contém os ativos estáticos que são servidos diretamente pelo servidor:

  * **`index.html`**: O principal arquivo HTML do seu aplicativo. É o ponto de entrada no navegador, onde o React injeta o conteúdo.
  * **`favicon.ico`**: O ícone que aparece na aba do navegador.
  * **`manifest.json`**: Um arquivo que descreve seu aplicativo web para navegadores, crucial para Progressive Web Apps (PWAs).

### `src/`

Aqui é onde toda a lógica e os componentes do seu aplicativo React residem. É o diretório de trabalho principal.

  * **`index.js`**: O ponto de entrada JavaScript. Ele inicializa o aplicativo React, renderizando o componente `App` no `index.html`.
  * **`App.js`**: O componente React de nível superior, onde você define a estrutura principal e as rotas do seu aplicativo para nutricionistas.
  * **`App.css`**: Estilos CSS específicos para o componente `App`.
  * **`index.css`**: Estilos CSS globais aplicados a todo o aplicativo.
  * **`App.test.js`**: Um exemplo de arquivo de teste para o componente `App`, utilizando o `@testing-library/react`.
  * **`logo.svg`**: Um exemplo de imagem SVG que pode ser usada em seus componentes.
  * **`reportWebVitals.js`**: Usado para medir métricas de desempenho web, como as Core Web Vitals, ajudando a monitorar a performance do seu aplicativo.

### `.gitignore`

Lista de arquivos e diretórios que o Git deve ignorar, como `node_modules/` e a pasta `build/`.

### `package.json`

O arquivo de configuração do projeto. Ele detalha os metadados do projeto, as dependências (`dependencies` para produção e `devDependencies` para desenvolvimento) e os scripts que você pode executar com `npm` (como `start`, `build`, `test`).

### `package-lock.json`

Gerado automaticamente pelo npm, este arquivo registra as versões exatas de todas as dependências e sub-dependências instaladas. Ele garante que todos os desenvolvedores que trabalham no projeto tenham o mesmo ambiente de dependências, prevenindo inconsistências.

### `README.md`

Este arquivo, que você está lendo, fornece uma visão geral do projeto, instruções de configuração e uso, e detalhes sobre a estrutura do código.

-----

Estamos animados para ver como o `nutribem-front` irá revolucionar o dia a dia dos nutricionistas\! Se tiver alguma dúvida ou sugestão, não hesite em nos contatar.
