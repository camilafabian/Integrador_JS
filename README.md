# Web de Gestión de Pedidos de Restaurante

Este proyecto tiene como objetivo crear una solución web que facilite la administración de los productos de un restaurante, así como la toma y seguimiento de los pedidos realizados por los clientes. La aplicación funciona directamente en el navegador y almacena los datos localmente, garantizando una experiencia continua para el usuario.

## Descripción General

La aplicación permite manejar de manera eficiente el menú del restaurante, registrar los pedidos que se hagan y visualizar el historial de todos los pedidos previamente registrados. Gracias a su diseño responsive, es compatible con una amplia gama de dispositivos.

## Funcionalidades Clave

- **Administración del Menú**: Agrega, edita o elimina productos del menú.
- **Pedidos de Clientes**: Facilita la creación de nuevos pedidos con productos seleccionados.
- **Historial de Pedidos**: Acceso rápido a los detalles de todos los pedidos anteriores.
- **Almacenamiento Persistente**: Los datos se guardan en el navegador usando LocalStorage, lo que permite que persistan entre sesiones.
- **Diseño Responsive**: Optimizado para ser utilizado en computadoras de escritorio, tablets y teléfonos móviles.

## Tecnología Implementada

El proyecto está construido utilizando herramientas web estándar:
- **HTML5** para la estructura del sitio.
- **CSS3** para el diseño y la adaptabilidad.
- **JavaScript** (ES6) para el manejo de la lógica y la interacción.
- **LocalStorage** para garantizar que los datos permanezcan disponibles entre sesiones del usuario.

## Pasos para la Instalación

Si deseas ejecutar el proyecto en tu entorno local, sigue estas indicaciones:

1. **Clona el repositorio:
   ```bash
   git clone https://github.com/camilafabian/Integrador_JS

2. **Accede a la carpeta donde se encuentra el proyecto**:
   ```bash
   cd IntegradorJS

3. ** Ejecuta con node.
   ```bash
   npm run dev

   
##Modo de Uso
- La aplicación ofrece varias opciones para la gestión de productos y pedidos:

### Buscar Productos: 
- Introduce un nombre en el campo de búsqueda para encontrar productos del menú.
### Añadir Nuevos Productos: 
- Completa el formulario con los detalles del producto (nombre, imagen, precio y categoría) y añádelo al menú.
### Realizar Pedidos: 
- Selecciona productos del menú y confirma el pedido ingresando los datos solicitados.
### Consultar Pedidos Anteriores:
- Accede a la sección de historial para ver los pedidos realizados anteriormente.
### Filtrar por Categoría:
- Utiliza el panel de categorías para mostrar solo los productos correspondientes a la categoría seleccionada.
