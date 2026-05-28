# DUB EDITION WEB

Web estática preparada para GitHub Pages.

## Archivos

- `index.html`: home principal.
- `rutas.html`: sección de rutas.
- `eventos.html`: historia de DUB21 en Circuit Ricardo Tormo junto a Probike Racing.
- `comunidad.html`: acceso al canal de Instagram.
- `unete.html`: formularios para empresas y miembros.
- `style.css`: diseño completo responsive.
- `script.js`: menú móvil, animaciones, pestañas y límite de 2 fotos.

## Subir a GitHub Pages

1. Sube todos los archivos al repositorio.
2. Ve a Settings > Pages.
3. Source: Deploy from a branch.
4. Branch: main.
5. Folder: / root.
6. Guarda y espera a que GitHub publique.

## Formularios

GitHub Pages no procesa formularios ni guarda archivos porque es hosting estático.

Opciones recomendadas:

### Opción rápida: Formspree

1. Crea cuenta en Formspree.
2. Crea un formulario para empresas y otro para miembros.
3. Copia el endpoint.
4. En `unete.html`, cambia `action=""` por tu URL de Formspree.

Ejemplo:

```html
<form class="form-card" action="https://formspree.io/f/xxxxxxx" method="POST">
```

Para el formulario del club con fotos, revisa que el servicio elegido permita subida de archivos.

### Opción muy fácil: Google Forms

Puedes sustituir los formularios por botones que abran dos Google Forms diferentes.

## Enlaces incluidos

- Instagram: https://www.instagram.com/dubeditionvlc
- Canal: https://www.instagram.com/channel/AbYgdCJDxc26Cs2u/?igsh=MzJocHFnZHQ5ZnM3
- Hashtag: #seguimosenlonuestro
