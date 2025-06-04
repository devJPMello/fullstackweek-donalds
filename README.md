# 🍔 FSW Donald's - Aplicativo de Pedido de Comida

**FSW Donald's** é um aplicativo de pedidos de comida desenvolvido durante a Full Stack Week, utilizando tecnologias modernas para proporcionar uma experiência de usuário fluida e eficiente.

🔗 [Acesse a aplicação online](https://fullstackweek-donalds-mauve.vercel.app)

---

## ✨ Funcionalidades

- 📋 Visualização do cardápio com categorias e produtos
- 🛒 Adição de produtos ao carrinho de compras
- 🧾 Finalização de pedidos com resumo detalhado
- 📱 Interface responsiva para dispositivos móveis
- 🔐 Autenticação de usuários (em desenvolvimento)

---

## 🚀 Tecnologias Utilizadas

- Next.js
- React
- TypeScript
- Tailwind CSS
- Prisma ORM
- PostgreSQL
- Vercel

---

## 🛠️ Como Executar Localmente

### Pré-requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn
- Banco de dados PostgreSQL

### Passo a passo

```bash
git clone https://github.com/devJPMello/fullstackweek-donalds.git
cd fullstackweek-donalds

npm install      # ou yarn
cp .env.example .env
npx prisma migrate dev
npm run dev      # ou yarn dev
```

Abra no navegador: http://localhost:3000

---

## 📁 Estrutura de Pastas

```
fullstackweek-donalds/
├── prisma/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   └── utils/
├── .env.example
├── next.config.js
├── package.json
└── README.md
```

---

## 📄 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

---

## 🙋‍♂️ Autor

Desenvolvido por [João Pedro Mendes de Mello](https://github.com/devJPMello)

Sinta-se à vontade para explorar, utilizar e contribuir para este projeto!
