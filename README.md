# EcoMarket 🌱

Sitio web académico de una tienda de demostración orientada al consumo responsable.

## Páginas
- **Inicio (`index.html`)**: hero, seis productos destacados y beneficios.
- **Productos (`views/productos.html`)**: catálogo de 20 productos, precios, disponibilidad, filtros visuales y paginación demostrativa.
- **Sobre nosotros (`views/sobre-nosotros.html`)**: historia, misión, visión, principios y testimonios ilustrativos.
- **Contacto (`views/contacto.html`)**: formulario HTML con validación nativa, información de contacto, imagen ilustrativa de mapa y enlaces sociales.

## Tecnologías
HTML5 semántico y CSS3 (Grid, Flexbox, Media Queries, transiciones y animaciones). No se utiliza JavaScript ni frameworks.

## Ejecutar localmente
1. Clona o descarga el repositorio.
2. Abre la carpeta en Visual Studio Code.
3. Abre `index.html` en un navegador o utiliza Live Server.

## Estructura
```text
EcoMarket_NombreApellido/
├── css/
│   ├── main.css
│   ├── layout.css
│   ├── components.css
│   └── animations.css
├── img/
│   ├── hero/
│   ├── products/
│   └── icons/
├── mockups/
│   ├── home-desktop.svg
│   ├── home-mobile.svg
│   ├── catalog-desktop.svg
│   ├── catalog-mobile.svg
│   ├── about-desktop.svg
│   ├── about-mobile.svg
│   ├── contact-desktop.svg
│   └── contact-mobile.svg
├── views/
│   ├── productos.html
│   ├── sobre-nosotros.html
│   └── contacto.html
├── index.html
└── README.md
```

## Limitaciones de la demo
El buscador, los filtros, la paginación y los favoritos son elementos visuales o de interacción limitada, porque el requisito excluye JavaScript. El formulario utiliza validación nativa, pero no envía datos a un servidor. Productos, precios, datos de contacto y testimonios son ilustrativos.

## Capturas
![alt text](image.png)
![alt text](image2.png)
![alt text](image3.png)
![alt text](image4.png)
![alt text](image5.png)

## GitFlow y ramas
El repositorio de entrega incluye ramas de trabajo organizadas:
- `main`: versión estable.
- `develop`: integración de funcionalidades.
- `feature/home`: inicio.
- `feature/catalogo`: catálogo.
- `feature/nosotros`: página sobre nosotros.
- `feature/contacto`: formulario y contacto.
- `feature/mockups`: wireframes de diseño.

Las ramas de funcionalidad se integran en `develop`; la versión estable se integra en `main`.
