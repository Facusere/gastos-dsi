# 💸 Gestión de Gastos Personales

Este proyecto es una aplicación web diseñada para registrar, visualizar, filtrar, editar, eliminar y analizar gastos mensuales. Permite a los usuarios tener un control claro y visual de sus finanzas personales.

---

## 🚀 Implementación (principal)

La aplicación está completamente desplegada en la nube, separando cada capa de la arquitectura:

- **Frontend (React + Vite + Tailwind)**  
  SPA construida con React y Vite, usando React Router para navegación.  
  ✅ Deploy: [Vercel](https://gastos-frontend-sigma.vercel.app/)

- **Backend (Node.js + Express)**  
  API RESTful conectada a Supabase para persistencia de datos.  
  ✅ Deploy: [Render](https://gastos-backend-anrz.onrender.com)

- **Base de Datos (Supabase - PostgreSQL)**  
  Base de datos alojada en Supabase con una tabla `expenses`.

### 🔌 Endpoints REST principales

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| GET    | `/api/expenses` | Obtener todos los gastos |
| GET    | `/api/expenses/:id` | Obtener gasto por ID |
| POST   | `/api/expenses` | Crear nuevo gasto |
| PUT    | `/api/expenses/:id` | Actualizar gasto existente |
| DELETE | `/api/expenses/:id` | Eliminar gasto |
| GET    | `/api/expenses?category=...` | Filtrar por categoría |
| GET    | `/api/expenses?month=AAAA-MM` | Filtrar por mes |
| GET    | `/api/reports/monthly?month=AAAA-MM` | Reporte mensual por categoría |

---

## 📷 Funcionalidades

- Registro de gastos con validación
- Visualización y filtrado por categoría o fecha
- Edición y eliminación de gastos existentes
- Generación de reporte mensual con gráfico
- Interfaz adaptativa y rápida

---

## 📁 Tecnologías utilizadas

### Frontend
- React + Vite
- TailwindCSS
- React Router
- Vercel (hosting)

### Backend
- Node.js + Express
- Supabase SDK
- Render (hosting)

### Base de Datos
- Supabase (PostgreSQL)
- Operaciones CRUD + reportes agrupados

---

## 🧪 Casos de prueba incluidos

- Registro de gasto correcto e inválido
- Visualización y validación de filtros
- Edición y eliminación de gasto
- Generación de reporte mensual
- Validación de formularios y feedback al usuario

---

## 🛠️ Enlaces útiles

🔗 [Repositorio Backend](https://github.com/Facusere/gastos-backend)  
🔗 [Repositorio Frontend](https://github.com/Facusere/gastos-frontend)  
🔗 [App en Vercel (Frontend)](https://gastos-frontend-sigma.vercel.app/)  
🔗 [API en Render (Backend)](https://gastos-backend-anrz.onrender.com)

---

## 📌 Autor

Facundo Sereno – Proyecto de gestión de gastos personales | 2025
