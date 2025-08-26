**🚀 Parcel Delivery API**

API para gerenciamento de entregas, com autenticação, controle de acesso e logs de status.

---

**✨ Funcionalidades**

🔑 Autenticação e gerenciamento de sessões de usuários

👤 Criação de usuários e controle de acesso (customer pode criar entregas)

📦 Gerenciamento de pedidos com atualização de status

📝 Logs de mudanças de status das entregas

---

**🛠 Tecnologias**

**Node.js | Express | Prisma | Zod | Jest | Insomnia | Beekeeper Studio | PostgreSQL (via Docker)**

---

**⚡ Como rodar**
```bash
git clone https://github.com/matheusgrigoleto/parcelDeliveryAPI.git
cd parcelDeliveryAPI
npm install
npm run build
npx prisma migrate dev
npm start
