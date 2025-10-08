# Wordle en Español - Little Bug Games

¡Bienvenido al Wordle en español de Little Bug Games! Una versión divertida y colorida del famoso juego de palabras.

## Descripción

Este proyecto es un juego de Wordle completamente funcional en español, construido sobre nuestro template personalizado de Little Bug Games. Características principales:

*   **Wordle en español**: Adivina palabras de 5 letras en español
*   **Interfaz hermosa**: Dos temas disponibles (Beautiful y Warrior) 
*   **Mariquita adorable**: Nuestro icono personalizado de Little Bug con variantes temáticas
*   **PWA completa**: Instala el juego en tu dispositivo
*   **Estadísticas**: Seguimiento de partidas, rachas y porcentaje de victorias
*   **Responsive**: Funciona perfectamente en móvil y escritorio
*   **Persistencia**: Guarda tu progreso y estadísticas localmente

## Estructura del Proyecto

```
Wordle/
├── index.html           # Juego completo de Wordle en un solo archivo
├── manifest.webmanifest # Manifiesto para PWA
├── sw.js               # Service Worker para funcionalidad offline
└── doc.md              # Este archivo
```

## Cómo Jugar

1. **Objetivo**: Adivina la palabra secreta de 5 letras en máximo 6 intentos
2. **Colores**: 
   - 🟩 Verde: Letra correcta en posición correcta
   - 🟨 Amarillo: Letra correcta en posición incorrecta  
   - ⬜ Gris: Letra no está en la palabra
3. **Controles**: Usa el teclado físico o virtual para escribir
4. **Nueva partida**: Haz clic en "Nueva" para empezar otra ronda

## Características Técnicas

*   **Una sola página**: Todo el juego está contenido en `index.html`
*   **Sin dependencias**: Funciona completamente offline
*   **PWA**: Instálalo como aplicación nativa
*   **Temas**: Alterna entre modo Beautiful (rosa) y Warrior (rojo)
*   **Responsive**: Optimizado para móvil y escritorio
*   **LocalStorage**: Guarda estadísticas y preferencias

## Despliegue en GitHub Pages

Para poner el juego en GitHub Pages:

1. **Repositorio**: Asegúrate de que los archivos estén en la rama `main` o `gh-pages`
2. **GitHub Pages**: Ve a Settings > Pages en tu repositorio
3. **Source**: Selecciona "Deploy from a branch" 
4. **Branch**: Elige `main` y folder `/ (root)`
5. **Guardar**: GitHub generará la URL de tu juego

## Personalización

Para personalizar el juego:

*   **Palabras**: Modifica el array `WORDS` en el JavaScript
*   **Colores**: Cambia las variables CSS en los temas
*   **Mariquita**: Edita los SVGs de las variantes Beautiful/Warrior
*   **Textos**: Actualiza los mensajes y títulos en español
*   **Estadísticas**: Añade nuevas métricas en el modal de stats

## Tecnologías Utilizadas

*   **HTML5**: Estructura semántica y accesible
*   **CSS3**: Grid, Flexbox, variables CSS, gradientes
*   **JavaScript**: ES6+, LocalStorage, eventos
*   **PWA**: Service Worker, Web App Manifest
*   **SVG**: Iconos vectoriales personalizados

---

¡Diviértete jugando y personaliza el juego a tu gusto! 🐞✨