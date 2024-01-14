# Product Manager

Este proyecto implementa una clase `ProductManager` en JavaScript, la cual gestiona un conjunto de productos. Forma parte del entregable de la Clase 2 del Curso de Backend, enfocándose en las nuevas funcionalidades de ECMAScript y la programación sincrónica y asincrónica.

## Características

- Creación de una clase `ProductManager` para gestionar productos.
- Funcionalidad para añadir productos con validación de campos únicos.
- Métodos para obtener todos los productos y buscar un producto por su ID.

## Instalación

Para utilizar este proyecto, clona el repositorio en tu máquina local:

```
git clone https://github.com/Backend2024/clase2.git 
```

## Uso
Aquí hay un ejemplo de cómo utilizar la clase ProductManager:  

```
const productManager = new ProductManager();

// Añadir un producto
productManager.addProduct("Producto Prueba", "Descripción del producto", 200, "url-imagen", "abc123", 25);

// Obtener todos los productos
console.log(productManager.getProducts());

// Obtener un producto por su ID
console.log(productManager.getProductById(1));  
```  

## Pruebas  

Se incluyen pruebas para validar la funcionalidad de la clase ProductManager, asegurando que:

- Se pueda añadir un nuevo producto con un ID único.  
- No se permita añadir productos con un código repetido.  
- Se puedan recuperar todos los productos y buscar un producto específico por su ID.    

## Contribuciones  

Las contribuciones son bienvenidas. Si deseas contribuir, por favor haz un fork del repositorio y crea un pull request, o simplemente abre un issue con la etiqueta "enhancements".

## Licencia
MIT
Este `README.md` proporciona una descripción general del proyecto, instrucciones sobre cómo instalarlo y usarlo, detalles sobre las pruebas realizadas y cómo contribuir. 
