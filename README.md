# 🍽️ Casa do Norte — Sistema de comandas para restaurante e mercearia

> **Vitrine do projeto.** O código-fonte é privado por ser um projeto de cliente.

🔗 **[Abrir a demonstração](https://north-house-two.vercel.app)**: a tela de login traz o acesso de demonstração, e os dados são de exemplo, salvos só no seu navegador.

Sistema de gestão para um **restaurante que funciona junto de uma mercearia de produtos regionais**. Começou como um e-commerce de delivery e foi adaptado para a operação do salão, com comandas, mesas, cardápio e mercearia no mesmo sistema.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=flat&logo=sequelize&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Mercado Pago](https://img.shields.io/badge/Mercado_Pago-00B1EA?style=flat&logo=mercadopago&logoColor=white)

## ✨ Funcionalidades

**Comandas**
- Tela única com comandas de **Local, Delivery e Retirada**, diferenciadas por cor
- Comanda local fica "Aberta" até o pagamento, com subtotal recalculado a cada item
- Pagamento em dinheiro, cartão ou **Pix (Mercado Pago)**
- Comprovante formatado para **impressora térmica de 80mm** (ou PDF) e opção de reabrir a comanda

**Mesas**
- Cadastro de mesas com status livre/ocupada, atualizado automaticamente pela comanda

**Produtos**
- Separação entre **Cardápio e Mercearia**
- Venda **por unidade ou por kg**, com baixa automática de estoque da mercearia

**Gestão**
- Relatórios **diários, semanais, mensais, semestrais e anuais**, com comparativo entre comandas locais e delivery
- Dashboard com tendência de faturamento, pedidos por status e ticket médio
- Cupons de desconto validados no servidor
- Notificações de novos pedidos no painel (toast e web push)

## 🏗️ Arquitetura

- **Backend:** API REST em Node.js/Express, Sequelize e MySQL, com autenticação JWT
- **Frontend:** SPA em React + Vite + Tailwind, com componentes reutilizáveis e skeletons de carregamento
- **Demonstração:** build do frontend com dados de exemplo no navegador, publicada na Vercel

---

Desenvolvido por **[Jolivan Abreu](https://github.com/JolivanAbreu)**.
