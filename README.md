# Chinese Sale – Client (Angular)

This repository contains the **Angular frontend** for the Chinese Sale project.
It provides the user interface for customers and administrators to interact with the system.

👉 Server (Web API) repository: [Chinese Sale – Server](https://github.com/Miriam-Salant/chinese-sale-server)

---

## 🚀 Features
- User registration & login (with validation: name, phone, email)
- View gifts with sorting and filtering (price, category)
- Add gifts to cart (saved as draft in DB)
- Confirm purchases (cannot delete after purchase)
- After lottery: 
- Display winners per gift 
- Purchasing is disabled

---

## 🛠️ Technologies
- Angular 18
- Angular Material
- TypeScript

---

## ⚙️ Setup & Run
```bash
git clone https://github.com/<your-username>/chinese-sale-client.git
cd chinese-sale-client
npm install
ng serve -o

The client will run on:
http://localhost:4200
