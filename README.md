🧪 Prueba Técnica – Frontend con Bun

Este proyecto es una aplicación frontend desarrollada con Bun cuyo objetivo principal es consumir, visualizar y organizar datos provenientes de una API REST.
Para la prueba se utiliza la Fake Store API, un servicio gratuito que proporciona datos ficticios de productos, categorías y usuarios.

⸻

🚀 Objetivo del Proyecto

Demostrar el uso de Bun en un entorno frontend para:
	•	📡 Consumir endpoints de una API REST.
	•	📊 Organizar y mostrar la información en componentes reutilizables.
	•	🔄 Manejar el flujo completo de peticiones HTTPS, estado y renderizado dinámico.

⸻

🛠️ Tecnologías Utilizadas
	•	⚡ Bun – runtime ultrarrápido para JavaScript.
	•	⚛️ React – librería para construir interfaces de usuario.
	•	🧰 Fetch API / Axios – para el consumo de la API.
	•	📁 Bun dev server – servidor de desarrollo.

⸻

📁 Estructura del Proyecto

├─ src/
│  ├─ components/   # Componentes de UI
│  ├─ pages/        # Vistas principales
│  ├─ services/     # Funciones para consumir la API
│  └─ App.jsx       # Punto de entrada principal
├─ bunfig.toml      # Configuración de Bun
├─ package.json     
└─ README.md


⸻

⚙️ Instalación y Ejecución
	1.	Clonar el repositorio:

git clone https://github.com/tu-usuario/bun-fakestore-app.git
cd bun-fakestore-app

2.	Instalar dependencias:
  ```
  bun i
  ```

  3.	Ejecutar el proyecto:
  ```
  bun dev
  ```

  4.	Abrir en el navegador:
  ```
  http://localhost:4000
  ```

⸻

🌐 API Utilizada

Se utiliza la Fake Store API de Platzi, que expone recursos como:
	•	🛍️ /products – Lista de productos

📚 Documentación oficial: https://fakeapi.platzi.com/en/about/introduction/

⸻

📌 Funcionalidades Clave
	•	🔎 Visualización de productos desde la API.
	•	🧭 Navegación simple entre vistas.
	•	♻️ Manejo de estados y renderizado dinámico.

	## Creen su propia rama (branch) y trabajen sobre ella
