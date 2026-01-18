# ✈️ Proyecto: Luna de Miel Indonesia 2026 🌴

![Estado del Proyecto](https://img.shields.io/badge/Estado-En_Despliegue-amber?style=for-the-badge)
![Tech](https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white)
![Design](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

> **"Un viaje se vive tres veces: al soñarlo, al vivirlo y al recordarlo."**
> Esta es la web oficial de la aventura de **Borja & Susan** por las islas de Indonesia. Un espacio interactivo para que nuestros invitados nos acompañen en la distancia. 🇮🇩

---

## ✨ Características Especiales

* **⏳ Cuenta Atrás en Tiempo Real:** Los segundos vuelan hasta el 22 de julio de 2026.
* **✨ Interfaz "Premium Gold":** Diseño minimalista en modo oscuro con acentos en dorado ámbar.
* **🦋 Efecto Luciérnagas:** Partículas animadas en CSS que dan vida al fondo de la web.
* **📱 Mobile First:** Optimizada específicamente para que los invitados la vean perfecta desde sus iPhone/Android.
* **🗺️ Itinerario Interactivo:** Mapa y detalles de cada parada (Ubud, Uluwatu, Seminyak, Gili T, Lombok).
* **📸 Integración WedShoots:** Sistema para que los invitados suban sus fotos directamente al álbum privado.

---

## 🛠️ Stack Tecnológico

| Herramienta | Uso |
| :--- | :--- |
| **Astro** | El motor de la web (Islands Architecture para máxima velocidad). |
| **Tailwind CSS** | Estilos modernos, responsivos y personalizados. |
| **Vercel** | Hosting y despliegue continuo (CD/CI). |
| **TypeScript/JS** | Lógica del contador y manejo de estados. |

---

## 📁 Estructura del Proyecto

```text
/
├── public/              # Imágenes locales, fotos de comida y el logo.
├── src/
│   ├── components/      # Componentes reutilizables (BentoItems, InfoPanels).
│   ├── layouts/         # Layout maestro con el Menú Dorado y Luciérnagas.
│   └── pages/           # Las secciones: Ruta, Sabores, Galería, etc.
└── tailwind.config.mjs  # Configuración de los tonos ámbar y fuentes.