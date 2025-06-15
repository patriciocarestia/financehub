# 💸 FinanceHub

**FinanceHub** es una aplicación full stack de finanzas personales desarrollada con **React** y **.NET 7**, que permite a los usuarios registrar ingresos y gastos, visualizar resúmenes mensuales y analizar sus hábitos financieros con gráficos dinámicos.

Este proyecto fue creado como ejercicio personal para aplicar buenas prácticas de desarrollo profesional, incluyendo **Clean Architecture**, **CQRS**, **AutoMapper**, **Unit Testing**, y más.

---

## 🧰 Tecnologías utilizadas

### 🔙 Backend (.NET 7)
- ASP.NET Core Web API
- Entity Framework Core
- AutoMapper
- MediatR (CQRS)
- FluentValidation
- Clean Architecture (Domain, Application, Infrastructure, API)
- Unit Testing con xUnit y Moq

### 🔜 Frontend (Node.js v23 + React)
- React 18+
- Axios
- React Router
- Tailwind CSS o Material UI (a definir)
- Chart.js o Recharts
- Context API o Redux Toolkit (según necesidad)

---

## 📂 Estructura del proyecto

FinanceHub/
├── backend/
│ └── src/
│ ├── FinanceHub.API/
│ ├── FinanceHub.Application/
│ ├── FinanceHub.Domain/
│ └── FinanceHub.Infrastructure/
└── frontend/
└── [próximamente]


---

## 🚀 Funcionalidades clave

- Autenticación de usuarios (JWT)
- ABM de transacciones (ingresos y egresos)
- Categorías de gastos
- Dashboard con resumen mensual
- Gráficos de torta y evolución mensual
- Filtros por categoría o fecha *(próximamente)*

---

## 🧪 Tests

Se incluyen tests unitarios para los `CommandHandlers`, `QueryHandlers` y validaciones de negocio, siguiendo el patrón AAA (Arrange, Act, Assert).

---

## 📦 Deploy

- Backend: Azure App Service *(pendiente)*
- Frontend: Vercel / Netlify *(pendiente)*

---

## 🧑‍💻 ¿Por qué este proyecto?

> Este proyecto fue desarrollado como demostración de mis conocimientos como Full Stack Developer, combinando una arquitectura profesional con funcionalidades reales de negocio, en un tiempo acotado pero con foco en la calidad del código.

---

## 📸 Capturas de pantalla

> *(Se agregarán en cuanto se avance con la UI)*

---

## 🔐 Usuario de demo (próximamente)

- **Email:** demo@financehub.com  
- **Contraseña:** Demo123!

---

## 📬 Contacto

Si te interesa ver el código o tenés feedback, podés contactarme por [LinkedIn](https://www.linkedin.com/in/patriciocarestia).
