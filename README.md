# 🌤️ Climax

### Seu clima. Em qualquer lugar. 🌎

**Um painel meteorológico moderno, responsivo e acessível, desenvolvido com TypeScript puro e Vanilla CSS.**

  <br />

[🌐 **Acessar o Climax**](https://alissonromaosantos.github.io/climax/)

  <br />

![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7+-646CFF?style=for-the-badge\&logo=vite\&logoColor=white)
![CSS](https://img.shields.io/badge/Vanilla_CSS-3-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![Open-Meteo](https://img.shields.io/badge/API-Open--Meteo-4CAF50?style=for-the-badge)

</div>

---

## 📝 Sobre o Projeto

**Climax** é um painel meteorológico moderno desenvolvido com foco em **performance, acessibilidade, responsividade e experiência do usuário**.

A aplicação utiliza **TypeScript puro**, sem frameworks frontend, combinando **HTML5 semântico** e **Vanilla CSS** para criar uma interface leve e eficiente.

Os dados meteorológicos são obtidos em tempo real através da **Open-Meteo API**, permitindo consultar condições climáticas de cidades ao redor do mundo. 🌎☁️

> 💡 **Sem frameworks pesados. Sem dependências desnecessárias. Apenas tecnologias web modernas.**

---

## 📱 Mobile-First & Responsividade

Um dos principais objetivos do Climax é proporcionar uma experiência consistente independentemente do dispositivo utilizado.

A interface foi desenvolvida seguindo a abordagem **Mobile-First**, começando pelo layout para telas menores e evoluindo progressivamente para tablets, notebooks e monitores maiores.

### 📐 Estratégia responsiva

* 📱 **Mobile First** — prioridade para dispositivos móveis
* 📲 Layout adaptável para tablets
* 💻 Experiência otimizada para desktops
* 🖥️ Aproveitamento de telas maiores
* 🧩 CSS Grid e Flexbox para construção dos layouts
* 📐 Breakpoints responsivos
* 👆 Componentes e controles adaptados para interação por toque
* 🔄 Conteúdo reorganizado de acordo com o tamanho da tela

O resultado é uma interface que mantém **usabilidade, legibilidade e organização visual** em diferentes resoluções.

---

## 📸 Demonstração

### 🌙 Tema Escuro

<p align="center">
  <img src="./src/assets/images/climax-dark-1.png" alt="Climax Dark Mode - Início" width="45%" />
  <img src="./src/assets/images/climax-dark-2.png" alt="Climax Dark Mode - Detalhes" width="45%" />
</p>

### ☀️ Tema Claro

<p align="center">
  <img src="./src/assets/images/climax-light-1.png" alt="Climax Light Mode - Início" width="45%" />
  <img src="./src/assets/images/climax-light-2.png" alt="Climax Light Mode - Detalhes" width="45%" />
</p>

---

## ✨ Funcionalidades

### 🔎 Busca Global

Pesquise cidades ao redor do mundo através de uma busca com **autocompletar inteligente**, facilitando a localização da cidade desejada.

### 📍 Geolocalização

Utilize a geolocalização nativa do navegador para consultar rapidamente as condições climáticas da sua localização atual.

### 📅 Previsão para 7 Dias

Visualize a previsão meteorológica dos próximos **7 dias**, incluindo:

* 🌡️ Temperaturas máximas e mínimas
* ☁️ Condições meteorológicas
* 📆 Previsão diária

### 📊 Métricas Meteorológicas

Consulte informações detalhadas sobre as condições atuais:

* ☀️ **Índice UV** — indicador de intensidade de 0 a 12
* 💨 **Vento** — velocidade em km/h e direção em graus
* 🌅 **Nascer do Sol**
* 🌇 **Pôr do Sol**
* 💧 **Umidade**
* 🌡️ **Sensação térmica**
* 👁️ **Visibilidade**
* 🌫️ **Qualidade do ar**
* 📈 **AQI** — índice de qualidade do ar dos Estados Unidos

### 🌎 Internacionalização

O Climax possui suporte a três idiomas:

* 🇧🇷 **Português — pt-BR**
* 🇺🇸 **Inglês — en-US**
* 🇪🇸 **Espanhol — es**

A interface pode adaptar o idioma de acordo com a configuração do usuário.

### 🌓 Temas

Escolha a aparência que melhor combina com você:

* ☀️ **Light**
* 🌙 **Dark**
* 🖥️ **System**

No modo **System**, a aplicação acompanha automaticamente a preferência de aparência configurada no sistema operacional.

### 🌡️ Unidade de Temperatura

Alterne instantaneamente entre:

* 🌡️ **Celsius (°C)**
* 🌡️ **Fahrenheit (°F)**

A preferência é persistida localmente para manter a configuração entre sessões.

### ♿ Acessibilidade

O projeto foi desenvolvido seguindo boas práticas de acessibilidade na Web, utilizando:

* 🏷️ HTML semântico
* 🎯 Atributos ARIA quando necessários
* ⌨️ Navegação por teclado
* 👁️ Estrutura adequada para leitores de tela
* 🔊 Informações e controles com semântica apropriada

---

## 🛠️ Tecnologias

| Tecnologia            | Utilização                                  |
| :-------------------- | :------------------------------------------ |
| 🟦 **TypeScript**     | Tipagem estática e organização da aplicação |
| ⚡ **Vite**            | Desenvolvimento e build do projeto          |
| 🧱 **HTML5**          | Estrutura semântica da aplicação            |
| 🎨 **Vanilla CSS**    | Estilização e responsividade                |
| 🌐 **Open-Meteo API** | Dados meteorológicos e qualidade do ar      |
| 🌎 **i18n**           | Internacionalização da aplicação            |
| 💾 **LocalStorage**   | Persistência das preferências do usuário    |
| 🧹 **ESLint**         | Análise e qualidade do código               |
| ✨ **Prettier**        | Padronização e formatação do código         |

---

## 🏗️ Arquitetura

O Climax foi desenvolvido sem frameworks frontend, utilizando uma arquitetura baseada em **módulos TypeScript**, componentes reutilizáveis e separação de responsabilidades.

A aplicação separa responsabilidades entre:

```text
API
 ↓
Estado da aplicação
 ↓
Componentes
 ↓
Renderização
 ↓
Interação do usuário
```

Essa abordagem facilita a manutenção, organização e evolução do projeto.

---

## 📂 Estrutura do Projeto

```text
climax/
│
├── public/
│   └── favicon.svg
│
├── src/
│   ├── api/
│   │   └── openMeteo.ts
│   │
│   ├── assets/
│   │   └── images/
│   │
│   ├── components/
│   │   ├── footer.ts
│   │   ├── header.ts
│   │   └── search.ts
│   │
│   ├── types/
│   │   └── index.ts
│   │
│   ├── app.ts
│   ├── i18n.ts
│   ├── main.ts
│   ├── storage.ts
│   ├── styles.css
│   └── utils.ts
│
├── package.json
├── tsconfig.json
├── eslint.config.mjs
└── vite.config.ts
```

### 📁 Principais diretórios

**`api/`**
Responsável pela comunicação com os serviços externos.

**`components/`**
Contém componentes reutilizáveis da interface.

**`types/`**
Centraliza interfaces e tipos utilizados pela aplicação.

**`assets/`**
Armazena imagens e outros recursos utilizados pelo projeto.

**`locales/` / `i18n.ts`**
Responsáveis pelo sistema de internacionalização.

**`storage.ts`**
Gerencia as preferências persistidas no `LocalStorage`.

**`utils.ts`**
Concentra funções utilitárias utilizadas em diferentes partes da aplicação.

**`styles.css`**
Contém a estilização global, responsividade, temas e layouts utilizando CSS moderno.

---

## 🚀 Como Executar

### 📋 Pré-requisitos

Antes de executar o projeto, certifique-se de possuir:

* 🟢 **Node.js**
* 📦 **npm**
* 🔧 **Git**

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/alissonromaosantos/climax.git
```

Entre no diretório:

```bash
cd climax
```

### 2️⃣ Instale as dependências

```bash
npm install
```

### 3️⃣ Execute em desenvolvimento

```bash
npm run dev
```

O Vite iniciará o servidor de desenvolvimento.

Normalmente, a aplicação estará disponível em:

```text
http://localhost:5173
```

### 4️⃣ Gere o build de produção

```bash
npm run build
```

Os arquivos otimizados serão gerados no diretório:

```text
dist/
```

### 5️⃣ Visualize a build

```bash
npm run preview
```

---

## 🧹 Qualidade de Código

O projeto utiliza **ESLint** e **Prettier** para manter o código consistente e facilitar a manutenção.

### 🔍 Executar ESLint

```bash
npm run lint
```

### 🔧 Corrigir problemas automaticamente

```bash
npm run lint:fix
```

### ✨ Formatar o projeto

```bash
npm run format
```

### ✅ Verificar formatação

```bash
npm run format:check
```

---

## 🌐 API

O projeto utiliza a **Open-Meteo API** para obter dados meteorológicos.

Entre as informações utilizadas estão:

* 🌡️ Temperatura
* 💨 Vento
* 💧 Umidade
* ☀️ Índice UV
* 🌅 Nascer e pôr do sol
* 📅 Previsão diária
* 👁️ Visibilidade
* 🌫️ Qualidade do ar
* 📍 Dados de localização

---

## 🚀 Deploy

O **Climax** está disponível online através do GitHub Pages.

<div align="center">

  <a href="https://alissonromaosantos.github.io/climax/">
    <img
      src="https://img.shields.io/badge/🌐%20Climax-Acessar%20Aplicação-2ea44f?style=for-the-badge"
      alt="Acessar Climax"
    />
  </a>

</div>

---

## 🎯 Objetivos do Projeto

O Climax foi desenvolvido com foco em colocar em prática conceitos importantes do desenvolvimento frontend moderno:

* 📱 Desenvolvimento **Mobile-First**
* 📐 Design responsivo
* ⚡ Performance
* ♿ Acessibilidade
* 🌎 Internacionalização
* 🧩 Arquitetura modular
* 🟦 TypeScript
* 🎨 CSS moderno
* 💾 Persistência local
* 🧹 Qualidade e padronização de código
* 🚀 Build e deploy

---

## 💡 Princípios

> **Mobile First 📱**
> A interface começa pelo menor dispositivo e evolui para telas maiores.

> **Accessibility ♿**
> Uma boa interface deve ser acessível para o maior número possível de pessoas.

> **Performance ⚡**
> Menos abstrações e dependências desnecessárias significam uma aplicação mais leve.

> **Simplicity 🧩**
> Utilizar as próprias tecnologias da Web quando elas são suficientes.

---

## 👨🏻‍💻 Autor

<div align="center">

  <img src="./public/favicon.svg" alt="Climax Logo" width="60" />

### Álisson Romão Santos

Desenvolvido com ❤️, ☕ e curiosidade em explorar novas habilidades em programação.

  <br />

  <a href="https://github.com/alissonromao">
    <img
      src="https://img.shields.io/badge/GitHub-Álisson%20Romão%20Santos-181717?style=for-the-badge&logo=github&logoColor=white"
      alt="GitHub"
    />
  </a>

</div>

---

<div align="center">

### ⭐ Gostou do projeto?

Se o **Climax** chamou sua atenção, considere deixar uma ⭐ no repositório!

  <br />

**© 2026 Climax**

  <br />

*Made with ❤️ and ☕ by Álisson Romão Santos*

</div>
