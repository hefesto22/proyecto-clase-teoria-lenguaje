# Proyecto Clase - Teoría del Lenguaje

Este es un proyecto desarrollado para la materia **Teoría del Lenguaje**, utilizando un stack moderno con **Laravel**, **Inertia.js**, **React** y **TypeScript**.

---

## 🚀 Tecnologías utilizadas

- **Laravel** (PHP): Framework backend que gestiona rutas, controladores, lógica y base de datos.
- **Inertia.js**: Librería que permite crear SPAs sin necesidad de APIs tradicionales.
- **React**: Biblioteca frontend para construir interfaces modernas e interactivas.
- **TypeScript (TSX)**: Superset de JavaScript que añade tipado estático y se usa junto con React para una mejor experiencia de desarrollo.
- **PHP**: Lenguaje base del backend.

---

## ⚙️ Requisitos del sistema

- PHP 8.1 o superior
- Composer
- Node.js y NPM
- Laravel 10 o superior
- Base de datos (MySQL, SQLite, etc.)

---

## 🛠️ Instalación y configuración

1. Clona el repositorio:
   ```bash
   git clone https://github.com/hefesto22/proyecto-clase-teoria-lenguaje.git
   cd proyecto-clase-teoria-lenguaje
composer install

npm install

cp .env.example .env

php artisan key:generate

php artisan migrate

php artisan db:seed

composer run dev 

Usuario: admin@gmail.com

Contraseña: 12345678
