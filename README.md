# 📲 QR Code Generator

Aplicação simples e personalizável para gerar QR Codes dinâmicos, com opção de adicionar cor, fundo e logo no centro.  

---

## Tecnologias

- [Next.js](https://nextjs.org/)  
- [TypeScript](https://www.typescriptlang.org/)  
- [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)  

---

## Funcionalidades

- Gere um QR Code a partir de um link/URL  
- Alterar cor do QR Code e fundo
- Upload de logo personalizada no centro do qrcode  
- Ajuste de tamanho da logo  
- Visualização em tempo real  
- Download do QR Code como imagem  

---

## Como rodar o projeto localmente

1. Clone este repositório  
   ```bash
   git clone https://github.com/Lussca000/qr-code-generator.git
2. Acesse a página do projeto
   ```bash
   cd qr-code-generator
3. Instale as dependências
   ```bash
   npm install
4. Inicie o servidor de desenvolvimento
   ```bash
   npm run dev
5. Abra no navegador:
   ```bash
   http://localhost:3000

 Estrutura do Projeto
   ```csharp
      📦 qr-code-generator
       ┣ 📂 app
       ┃ ┗ 📜 page.tsx   # Pagina principal da aplicaçao
       ┣ 📂 public       # Estaticos (imagens, logos, etc.)
       ┣ 📜 package.json # Configuração do projeto
       ┣ 📜 tsconfig.json
       ┗ ...
