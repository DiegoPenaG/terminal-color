# 🏁 Terminal Color

<p align="center">
  <a href="https://github.com/DiegoPenaG/terminal-color" target="_blank">
    🔗 Ver repositorio en GitHub
  </a>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-18+-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/npm-gestor_de_paquetes-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/chalk-colores_en_consola-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/estado-completado-success?style=for-the-badge" />
</p>

---

## 🎯 Objetivo

Desarrollar un programa en JavaScript que simule una terminal interactiva, aplicando:

* Uso de **Node.js y npm**
* Instalación de dependencias externas
* Uso de distintos tipos de `console`
* Trabajo colaborativo con **Git y GitHub**

---

## 🧩 Descripción del proyecto

**La Terminal Parlante** es una aplicación de consola que muestra mensajes estilizados con colores, simulando:

* Estados de ejecución
* Advertencias
* Errores controlados
* Mensajes informativos

---

## 🚀 Tecnologías utilizadas

| Tecnología       | Uso                     |
| ---------------- | ----------------------- |
| JavaScript (ESM) | Lógica del programa     |
| Node.js          | Entorno de ejecución    |
| npm              | Gestión de dependencias |
| chalk            | Estilos en consola      |

---

## 📦 Instalación

```bash
git clone https://github.com/DiegoPenaG/terminal-color.git
cd terminal-color
npm install
```

---

## ▶️ Ejecución

```bash
npm start
```

o

```bash
node index.js
```

---

## 🧠 Funcionalidades

### 👋 Mensajes iniciales

Uso de:

* `console.log`
* `console.info`
* `console.warn`
* `console.error`

---

### 🟦 `saludar(nombre)`

Entrega un saludo personalizado.

---

### 🟩 `mostrarEstado()` — Equipo A

Simula el flujo de ejecución de un programa:

* 🚀 Inicio
* 🔄 Proceso
* ⚠️ Advertencia
* ❌ Error simulado
* ✅ Finalización exitosa

---

### 🟥 `simularError()` — Equipo B

Simula un error controlado:

* ⚠️ Advertencia
* ❌ Error
* ✅ Recuperación

---

## 📁 Estructura del proyecto

```bash
terminal-color/
│
├── index.js
├── package.json
├── package-lock.json
└── .gitignore
```

---

## 🧪 Ejemplo de salida

```bash
👋 ¡Bienvenido a la Terminal Parlante!
ℹ️ Esta terminal está viva... y tiene estilo.
⚠️ Atención: Esto puede ponerse colorido.
❌ Error simulado: algo salió demasiado bien.
💡 Recuerda: la práctica hace al programador.

Hola Equipo JS, ¡bienvenido al mundo JavaScript! 🌍

🚀 Iniciando programa...
🔄 Proceso en ejecución...
⚠️ Casi listo...
❌ Simulación de error leve
✅ Programa finalizado correctamente

⚠️ Advertencia: algo podría fallar...
❌ Error: algo falló!
✅ Recuperación exitosa
```

---

## ⚠️ Buenas prácticas aplicadas

* Uso de `"type": "module"` en `package.json`
* Exclusión de `node_modules/` con `.gitignore`
* Uso de ramas (`feature/equipoA`, `feature/equipoB`)
* Commits descriptivos
* Uso de Pull Requests

---

## 👥 Trabajo colaborativo

* Desarrollo en ramas separadas
* Integración mediante Pull Request
* Merge a rama principal (`main`)
* Sincronización del equipo

---

## 🎓 Aprendizajes clave

* Gestión de dependencias con npm
* Uso de módulos en JavaScript
* Diferencias entre tipos de `console`
* Flujo de trabajo profesional con Git

---

## 💡 Frase final

> “Un buen programador no evita errores, aprende a controlarlos.”

---
