# 🚀 Landing Page Responsiva | React + Tailwind CSS

Uma **Landing Page moderna, rápida e totalmente responsiva**, desenvolvida com **React.js** e **Tailwind CSS**.  
O projeto conta com **Navbar interativa**, **seções animadas**, **cards de preços**, **vídeos integrados** e **design otimizado para mobile e desktop**.  

---

## 🧩 Tecnologias Utilizadas

- ⚛️ **React.js** — Biblioteca JavaScript para construção da interface.  
- 💨 **Tailwind CSS** — Framework CSS utilitário para estilização rápida e responsiva.  
- ⚡ **Vite** — Ferramenta de build ultrarrápida para projetos React modernos.  
- ☁️ **Vercel** — Plataforma de deploy e hospedagem.

---

## 🛠️ Instalação e Configuração

Siga os passos abaixo para executar o projeto localmente:

```bash
# 1️⃣ Crie o projeto com Vite
npm create vite@latest landing-page --template react

# 2️⃣ Acesse o diretório do projeto
cd landing-page

# 3️⃣ Instale as dependências
npm install

# 4️⃣ Instale o Tailwind CSS e dependências
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

# 5️⃣ Configure o Tailwind
# Adicione no arquivo tailwind.config.js:
content: [
  "./index.html",
  "./src/**/*.{js,ts,jsx,tsx}",
]

# 6️⃣ Importe o Tailwind no seu CSS principal (ex: index.css)
@tailwind base;
@tailwind components;
@tailwind utilities;

# 7️⃣ Execute o servidor de desenvolvimento
npm run dev


🧱 Estrutura do Projeto

landing-page/
├── public/
├── src/
│   ├── assets/           # Imagens, vídeos e ícones
│   ├── components/       # Componentes reutilizáveis (Navbar, Cards, Footer, etc)
│   ├── pages/            # Seções principais da Landing Page
│   ├── App.jsx
│   └── index.css
├── package.json
├── tailwind.config.js
└── vite.config.js

🌐 Funcionalidades da Landing Page
🔝 Navbar Responsiva

Menu fixo no topo com logo e links de navegação.

Drawer lateral (menu hamburguer) no modo mobile.

🎬 Seção Hero

Título com texto em gradiente para um visual moderno.

Vídeo em autoplay e loop integrando movimento à interface.

💡 Seção de Recursos (Features)

Lista de recursos e benefícios do produto com UI limpa e minimalista.

Layout adaptável para todas as telas.

💳 Planos e Preços

Três cards de planos com diferentes ofertas.

Destaque visual para o plano mais popular.

💬 Depoimentos

Seção de testemunhos de clientes satisfeitos.

Design elegante e responsivo.

🧭 Rodapé (Footer)

Links rápidos, ícones sociais e direitos autorais.

🌈 Responsividade

Totalmente otimizado para:

📱 Mobile (telas pequenas)

💻 Desktop (telas médias e grandes)

Construído com Tailwind CSS breakpoints para adaptação automática.

🚀 Deploy na Vercel

O deploy é simples e rápido:

# Build do projeto
npm run build


Em seguida:

Crie uma conta em https://vercel.com
.

Conecte o repositório do GitHub.

A Vercel detectará automaticamente o projeto React + Vite.

Clique em Deploy e o site estará online em poucos segundos.

🧠 Aprendizados

Durante o desenvolvimento, você aprenderá a:

Configurar Tailwind CSS em projetos React com Vite.

Criar layouts modernos e responsivos.

Trabalhar com componentização no React.

Integrar vídeos e animações na web.

Realizar deploy profissional na Vercel.

📸 Prévia

(Adicione aqui uma imagem ou GIF da Landing Page, ex: /src/assets/preview.png)

🧑‍💻 Autor

Desenvolvido por [Fabiano Forte Ferreira]
💼 GitHub: https://github.com/seunome

🌐 Versão Web: https://seusite.com
