# **Evaluación Final Módulo 1**

## 🔎**Descripción del proyecto:**

Este repositorio contiene la solución para la evaluación final del Módulo 1 de Data Analytics. El proyecto consiste en implementar un sistema de gestión de una tienda online utilizando la Programación Orientada a Objetos (OOP).

## 🏗️**Estructura del proyecto:**

El proyecto está organizado alrededor de dos clases principales implementadas en un Jupyter Notebook:

1. TiendaOnline: Contiene la lógica principal del inventario y las ventas, incluyendo métodos:

* **`agregar_producto`**: Implementa lógica para añadir nuevos artículos o actualizar automáticamente las unidades de productos existentes.
* **`ver_inventario`**: Genera un reporte detallado y formateado de todos los artículos, incluyendo nombre, precio y stock.
* **`buscar_producto`**: Localiza ítems específicos y muestra su información detallada de forma inmediata.
* **`actualizar_stock`**: Gestiona entradas y salidas de mercancía de forma manual.
* **`eliminar_producto`**: Limpia el catálogo eliminando productos obsoletos o fuera de registro.
* **`calcular_valor_inventario`**: Ejecuta una auditoría financiera calculando el valor monetario total de todo el almacén.


2. TiendaOnlineDos: Hereda de TiendaOnline y extiende su funcionalidad añadiendo una capa de CRM (Customer Relationship Management) y ventas. Con ella puedes:

* **`agregar_cliente`**: Registra nuevos usuarios en una base de datos indexada por nombre, evitando duplicados.
* **`ver_clientes`**: Visualiza de forma rápida el listado de clientes registrados y sus correos electrónicos.
* **`realizar_compra`**: Flujo interactivo que permite seleccionar productos, verificar stock en tiempo real y actualizar el inventario tras la confirmación.
* **`procesar_pago`**: Gestiona la transacción financiera de forma segura, incluyendo el cálculo de cambio y manejo de errores (excepciones).
* **`registrar_compra`**: Archiva cada transacción en el historial específico del cliente y actualiza las ventas totales de la tienda.
* **`ver_compras_cliente`**: Accede al historial de pedidos de un usuario para conocer sus hábitos de consumo.
* **`calcular_ventas_totales`**: Muestra el rendimiento económico acumulado de todas las operaciones realizadas.

## 🛠️**Tecnologías y Conceptos Aplicados:**

El desarrollo de este sistema de gestión se basa en pilares fundamentales de la ingeniería de software y el análisis de datos con Python:

### **Tecnologías Core**
* **Python 3.x**: Lenguaje principal utilizado para toda la lógica de programación.
* **Jupyter Notebook**: Entorno de desarrollo interactivo utilizado para la implementación, documentación y pruebas unitarias del código.

### **Conceptos de Programación Avanzada**
* **Programación Orientada a Objetos (POO)**: 
    * **Clases y Objetos**: Estructuración del sistema mediante entidades `TiendaOnline` y `TiendaOnlineDos`.
    * **Herencia**: La clase `TiendaOnlineDos` hereda atributos y métodos de la clase madre, permitiendo la reutilización de código y la especialización de funciones.
    * **Métodos de Instancia**: Implementación de lógica propia para cada objeto (ej. `agregar_producto`, `realizar_compra`).
* **Gestión de Errores y Robustez**: 
    * **Manejo de Excepciones (`try...except`)**: Implementado específicamente en procesos críticos como el pago y la entrada de datos numéricos para evitar caídas del sistema ante inputs erróneos.
* **Control de Flujo Complejo**: 
    * Uso de bucles `while` condicionales para flujos de compra continuos y bucles `for` con sentencias `break`/`continue` para búsquedas eficientes en el inventario.

### **Estructuras de Datos y Lógica de Negocio**
* **Modelado de Datos**: 
    * **Diccionarios Anidados**: Uso de estructuras complejas para representar clientes, donde cada clave contiene otro diccionario con emails e historiales de compra.
    * **Listas de Diccionarios**: Gestión del inventario para mantener la mutabilidad y el acceso rápido a propiedades como 'precio' o 'cantidad'.
* **Lógica de Auditoría**: Implementación de algoritmos para el cálculo automático de ventas totales y valoración de activos (stock) en tiempo real.

## 🚀**Ejecución del proyecto:**

Para probar la implementación, sigue estos pasos:
1. **Clona el repositorio en tu terminal**. Abre tu terminal y descarga el proyecto: git clone https://github.com/arantxa-90/evaluacion-modulo1-da-promo-64-arantxa-barea.git
2. **Abre el Notebook**: Localiza el archivo evaluacion_final_modulo_1_da_arantxa_barea_VF `.ipynb` en tu entorno de Jupyter.
3. **Ejecuta secuencialmente todas las celdas**: Podrás visualizar los resultados de cada método implementado.

## 💡**Autora:**

**Arantxa Barea** | [🔗 LinkedIn](https://www.linkedin.com/in/arantxa-barea/) 