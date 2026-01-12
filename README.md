# Localizar - Plataforma de Gestión Comercial Digital

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)

> **Nota:** Este repositorio sirve como documentación técnica y portafolio del proyecto **Localizar**. Debido a la naturaleza comercial del producto (SaaS), el código fuente es privado.

---

## 💡 Sobre el Proyecto
**Localizar** es un ecosistema digital diseñado para conectar negocios locales con clientes a través de un catálogo interactivo, sistema de reservas y mapas. Como **Frontend Lead**, lideré la arquitectura del cliente web, enfocándome en la escalabilidad, el tipado estricto y la experiencia de usuario.

---

## 🛠 Stack Tecnológico y Decisiones Técnicas

El proyecto fue migrado y desarrollado utilizando un stack moderno para asegurar **Performance** y mantenibilidad:

### Frontend Core
* **React + TypeScript:** Uso extensivo de TypeScript para garantizar la seguridad de tipos en componentes y contratos de API.
* **Arquitectura de Estado:** Implementación de un manejo de estado global personalizado (Context API + Hooks avanzados) para gestionar sesiones de usuario, carrito de compras y filtros de búsqueda sin depender de librerías pesadas innecesarias.
* **Fetching de Datos:** Capa de servicios desacoplada para el consumo de API REST, con manejo de caché y estados de carga/error optimizados.

### UI/UX & Estilos
* **TailwindCSS:** Sistema de diseño utility-first para un maquetado rápido y consistente.
* **Diseño Responsive:** Enfoque *Mobile First* utilizando Flexbox y Grid para asegurar compatibilidad total en dispositivos móviles.
* **UX Dinámica:** Feedback visual inmediato (toast notifications, loaders, skeleton screens) para mejorar la percepción de velocidad.

---

## 🚀 Desafíos Superados

### 1. Arquitectura Limpia en Frontend
Para evitar componentes "espagueti", implementé patrones de diseño que separan la lógica de negocio de la vista.
* *Solución:* Uso de **Custom Hooks** que actúan como "Controllers", dejando a los componentes de React puramente presentacionales.

### 2. Optimización de Performance
El dashboard maneja grandes volúmenes de datos de todo el ecosistema.
* *Solución:* Implementación de paginación desde el servidor y `memoización` de componentes clave para evitar re-renders innecesarios al manipular grandes tablas de datos.

---

## 📸 Galería del Proyecto

### 1. Backoffice Administrativo (Internal Tool)
*Panel de control centralizado para la administración total del ecosistema, métricas globales y gestión de usuarios.*
<br>
**⚠️ Nota:** *Los datos numéricos y KPIs mostrados en esta captura son ficticios generados únicamente para fines de demostración y no reflejan métricas reales del negocio.*

<div align="center">
  <img src="https://github.com/user-attachments/assets/a81402e0-4b37-4707-912e-256078255b11" alt="Dashboard Localizar" width="100%" style="border-radius: 10px; box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);">
</div>

<br>

### 2. Vista Pública Mobile
*Experiencia de usuario final enfocada en Mobile Only*
<div align="center">
  <img src="https://github.com/user-attachments/assets/b74bf828-c380-4bce-a6a9-da3624e64c29" alt="Mobile Public View" height="600" style="border-radius: 15px; border: 2px solid #333;">
  <p><a href="https://localizar.website">🔗 Visitar Localizar.website</a></p>
</div>

---

## 📬 Contacto
**Néstor David Gariglio**
* Desarrollador Frontend React
* [Email](mailto:nestorgariglio33@gmail.com)
