# 🧑‍🍳 Recipe App

Um aplicativo simples e interativo que utiliza inteligência artificial para **criar receitas** com base nos ingredientes que você já tem em casa. Basta adicionar os itens à sua lista e o app gera uma receita personalizada usando IA via Hugging Face.

---

## ✨ Funcionalidades

- ✅ Adicione ingredientes à sua lista
- 🤖 Gere receitas com base na sua despensa
- 📝 Veja o resultado formatado com Markdown
- ⚡ Interface leve, responsiva e fácil de usar

---

## 🧠 Inteligência Artificial

Este projeto utiliza a API de inferência da [Hugging Face](https://huggingface.co/) para gerar sugestões de receitas a partir dos ingredientes informados pelo usuário.

---

## 🧪 Tecnologias Utilizadas

- **React 19** – biblioteca principal para a interface
- **Vite** – ferramenta de build e servidor de desenvolvimento
- **@huggingface/inference** – integração com a IA
- **React Markdown** – renderização das receitas com Markdown
- **ESLint** – linting para garantir boas práticas de código

---

## 🔐 Configurando a API da Hugging Face

Para o app funcionar corretamente, é necessário um token de API da Hugging Face.

### 1. Criar uma conta

Acesse [https://huggingface.co](https://huggingface.co) e crie uma conta gratuita.

### 2. Obter seu token

- Vá até **Settings > Access Tokens**
- Clique em **New token**
- Copie o token gerado (formato: `hf_xxxxxxxxxx`)

### 3. Criar um arquivo `.env` na raiz do projeto

Crie um arquivo `.env` com o seguinte conteúdo:

VITE_HUGGINGFACE_API_KEY=seu_token_aqui

> Substitua `seu_token_aqui` pelo token copiado da Hugging Face.

### 4. Rodar o projeto

Após salvar o arquivo `.env`, reinicie o servidor de desenvolvimento com:

npm run dev

---

## ▶️ Como rodar o projeto localmente

### 1. Clone o repositório

git clone https://github.com/Celsocag/recipe-app.git
cd recipe-app

### 2. Instale as dependências

npm install


### 3. Inicie o servidor

npm run dev
Acesse o app em: http://localhost:5173


🚀 Build para produção
bash
Copiar
Editar
npm run build
📦 Deploy
Este projeto pode ser facilmente hospedado com:

Vercel

Netlify

Surge.sh

📌 Requisitos
Node.js 18+

Conta e token de API no Hugging Face
