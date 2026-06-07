# PokedexApi 🎮

Una aplicación web de Pokédex desarrollada con React que consume la [PokeAPI](https://pokeapi.co/) para mostrar información detallada de los Pokémon.

## 🚀 Demo

[Ver proyecto en GitHub](https://github.com/JonatanGil/pokedexApi)

---

## 🛠️ Tecnologías

- **React** — Biblioteca principal de UI
- **PokeAPI** — API REST pública de Pokémon
- **HTML5 / CSS3** — Maquetación y estilos
- **JavaScript (ES6+)** — Lógica de la aplicación

---

## 📋 Funcionalidades

- Listado de Pokémon obtenido en tiempo real desde la PokeAPI
- Visualización de detalles de cada Pokémon
- Lógica de devolución/navegación entre Pokémon (`DevolverPokemones.js`)
- Service Worker incluido para soporte offline (PWA)

---

## ⚙️ Instalación y uso

### Requisitos previos

- Node.js >= 14
- npm

### Pasos

```bash
# Clonar el repositorio
git clone https://github.com/JonatanGil/pokedexApi.git

# Entrar en la carpeta del proyecto
cd pokedexApi/pokedex

# Instalar dependencias
npm install

# Iniciar la aplicación en modo desarrollo
npm start
```

La app estará disponible en `http://localhost:3000`

### Build para producción

```bash
npm run build
```

---

## 📁 Estructura del proyecto

```
pokedexApi/
└── pokedex/
    ├── public/
    │   ├── index.html
    │   ├── favicon.ico
    │   ├── logo192.png
    │   ├── logo512.png
    │   ├── pokeapi.png
    │   ├── manifest.json
    │   └── robots.txt
    ├── src/
    │   ├── App.js
    │   ├── App.css
    │   ├── App.test.js
    │   ├── DevolverPokemones.js
    │   ├── index.js
    │   ├── index.css
    │   ├── logo.svg
    │   ├── serviceWorker.js
    │   └── setupTests.js
    ├── .gitignore
    ├── package.json
    ├── package-lock.json
    └── README.md
```

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún bug o tienes alguna mejora, abre un issue o un pull request.

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT.

---

## 👤 Autor

**Jonathan Gil Galera**  
GitHub: [@JonatanGil](https://github.com/JonatanGil)
