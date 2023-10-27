# Prueba Técnica para Desarrollador de Next.js

## Objetivo:

Desarrollar una aplicación simple en Next.js que permita listar los personajes de Rick y Morty y añadir nuevos personajes a la lista.

## Recursos:

- **API de Rick y Morty**: [Documentación](https://rickandmortyapi.com/documentation)
- Repositorio provisto con Next.js instalado.

## Instrucciones:

### 1. Configuración Inicial:

- Clona el repositorio provisto y asegúrate de tener las dependencias necesarias instaladas (`npm install` o `yarn install`).

### 2. Integración con la API:

- Utiliza la API de Rick y Morty para obtener la lista de personajes.
- Muestra la lista de personajes en el componente provisto para la lista.

### 3. Desarrollo del Componente de Lista (`CharactersList`):

- Dentro del componente de lista, muestra los nombres de los personajes obtenidos desde la API.

### 4. Desarrollo del Componente de Formulario (`Form`):

- Crea un formulario simple que permita al usuario ingresar el nombre de un nuevo personaje.
- Una vez el usuario envíe el formulario, añade este nuevo personaje a la lista existente.
- El formulario debe ser generado con react-hook-form y validado con yup.

### 5. Estilo y Presentación:

- Aunque la funcionalidad es más importante, se valora un diseño básico y limpio.
- Asegúrate de que la aplicación sea responsiva y tenga una buena usabilidad.

### 6. Bonificación (opcional pero valioso):

- Añade alguna característica extra que consideres podría enriquecer la aplicación.
- Implementa manejo de errores básico, en caso de que la API no esté disponible o surja algún problema.
