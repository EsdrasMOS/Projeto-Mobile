**🚀Projeto Mobile**

Este é um projeto de jogo do estilo TCG (Trading Card Game), utilizando personagens de franquias famosas da Marvel Comics. O nosso "Jogo-Trunfo" tem uma mecânica de contabilização do poder total do personagem que avalia se o personagem escolhido pelo jogador tem poder base inferior ou superior ao oponente.

---

**📌 Sobre o projeto**

- A falta de jogos concisos no momento de avaliar a força entre personagens acaba sendo, muitas vezes desproporcional ou sem graça.
- Neste contexto, criamos um jogo com uma variedade massiva de personagens interagindo de forma mais precisa ao que vemos nos quadrinhos.
- Esse projeto se iniciou como um projeto acadêmico com o objetivo de praticar o consumo de API, framework Angular com Ionic e reforçar os ensinamentos para o desenvolvimento de aplicações mobile.

---

**🛠️ Tecnologias utilizadas**

- Linguagem: TypeScript, Html, Sass, JSON
- Frameworks e Bibliotecas: Angular, Ionic
- Outras ferramentas: Git e Superhero API

---

**⚙️ Funcionalidades**

- Barra de pesquisa de personagens.
- Mecânica de batalha.
- Tela responsiva ao dispositivo.
- Média precisa de poder de cada personagem.
- CGerador automático de batalhas.

---

**📁 Estrutura do projeto**

```bash
📦 Projeto-Mobile
 ┣ 📂 jogo-trunfo
 ┃  ┣ 📂 src
 ┃  ┃  ┣ 📂 app
 ┃  ┃  ┃  ┣ 📂 directives
 ┃  ┃  ┃  ┃  ┗ 📜 powerful.ts
 ┃  ┃  ┃  ┣ 📂 game
 ┃  ┃  ┃  ┃  ┣ 📜 game.page.html
 ┃  ┃  ┃  ┃  ┣ 📜 game.page.ts
 ┃  ┃  ┃  ┃  ┗ 📜 game.page.scss
 ┃  ┃  ┃  ┣ 📂 home
 ┃  ┃  ┃  ┃  ┣ 📜 home.page.html
 ┃  ┃  ┃  ┃  ┣ 📜 home.page.ts
 ┃  ┃  ┃  ┃  ┗ 📜 home.page.scss
 ┃  ┃  ┃  ┣ 📂 pipes
 ┃  ┃  ┃  ┃  ┗ 📜 power-total-pipes.ts
 ┃  ┃  ┃  ┗ 📂 services
 ┃  ┃  ┃     ┗ 📜 superhero.ts
 ┃  ┃  ┗ 📜 index.html
 ┃  ┣ 📜 tsconfig.app.json
 ┃  ┣ 📜 tsconfig.json
 ┃  ┗ 📜 tsconfig.spec.json
 ┗ 📜 README.md

 ```

---

## ⚙️ Guia de Instalação

Siga os passos abaixo para configurar e rodar o projeto localmente.

### 📋 Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas na sua máquina:
- **Node.js** (versão 20.x ou superior recomendada)
- **npm** (gerenciador de pacotes, já incluso no Node.js)
- **Ionic CLI** (opcional, mas recomendado): `npm install -g @ionic/cli`
- **Android Studio** (apenas se for rodar ou buildar para dispositivo Android)

### 🚀 Passo a Passo para PC

```Clone o repositório
git clone <URL_DO_SEU_REPOSITORIO>
cd jogo-trunfo
```

````Instale as dependência
npm install
````

````Execute o projeto no navegador
npm start
# ou, se tiver o Ionic CLI instalado:
ionic serve
````

### Passo a Passo Mobile

````Sicroniza os arquivos com o Capacitador
npx cap sync android
````


````Abre no Android Studio
npx cap open android
````

**No Android Studio:**
- Aguarde a sincronização do Gradle.
- Conecte um dispositivo físico ou inicie um emulador.
- Clique no botão Play (Run) para compilar e instalar o app.

