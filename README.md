Aplicación web sencilla construida con **React + Vite**.

## Tema y Objetivo
**Tema:** Veterinaria — Catálogo de razas de perros (con favoritos).  
**Objetivo:** Crear una interfaz interactiva y responsiva que consuma una **API pública**, gestione **estado**, use **router** para navegación y aplique **buenas prácticas** de estructura y estilos.

## Requisitos Funcionales
1. **Interfaz de usuario interactiva y responsiva**
   - Diseño adaptativo con CSS y grid.
2. **Componentes funcionales en React**
   - Componentes: `NavBar`, `Card`, `Loader`, `ErrorBox`.
3. **Consumo de API pública**
   - `TheDogAPI` (`/v1/breeds`) usando Axios en `services/api.js`.
4. **React Router para navegación**
   - Rutas: `/` (Inicio), `/catalogo`, `/favoritos`, `/acerca`.
5. **Estilos con CSS**
   - Archivo `src/styles.css` con diseño moderno.
6. **Código bien estructurado**
   - Carpeta `src` organizada por **components**, **pages**, **services**, **hooks**.

## Tecnologías
- React 18, React Router 6
- Axios
- Vite

## Guyia de ejecución local

```bash
# 1) Instalar dependencias
npm install

# 2) Correr en desarrollo
npm run dev

# 3) Build de producción
npm run build
npm run preview

## Créditos
- API pública: [TheDogAPI](https://thedogapi.com) (endpoint `/v1/breeds`).
```
