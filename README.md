# Test Web-scraper Tech-K

## Instrucciones de uso
---

1. [Duplicar](https://help.github.com/es/github/creating-cloning-and-archiving-repositories/duplicating-a-repository) el proyecto
2. Cambiar su [visibilidad](https://help.github.com/es/github/administering-a-repository/setting-repository-visibility) a privado
3. Agregar al usuario `point-techk-devs` como colaborador dentro del repositorio
4. Desarrollar lo que se indica en la siguiente sección en Python3. Si existen supuestos, estos deben definirse claramente en el README
5. Notificar mediante email cuando este listo y enviar el link del repositorio privado.

## Instrucciones de desarrollo
---

1. Buscar todos los libros (recorrer la paginación) de este link: http://books.toscrape.com/
2. De cada libro se debe obtener la siguiente información:
    * Title
    * Price
    * Stock
    * Category (Travel, Mystery, Historical Fiction, etc)
    * Cover (url de la carátula del libro)
    * Product Description
        * UPC
        * Product Type
        * Price (excl. tax)
        * Price (incl. tax)
        * Tax
        * Availability
        * Number of reviews
3. Los resultados se deben exportar en un archivo CSV con las siguientes cabeceras:
    * Title
    * Price
    * Stock
    * Category
    * Cover
    * UPC
    * Product Type
    * Price (excl. tax)
    * Price (incl. tax)
    * Tax
    * Availability
    * Number of reviews
4. Se debe incluir un archivo requeriments.txt con las dependencias que requiera el script.

## Bonus que suman puntos
---
* Usar las librerías [Requests](http://docs.python-requests.org/en/master/) y [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* Uso de tests unitarios

## En qué nos fijaremos
---
* Correcto uso de GIT
* Patrones de diseño
* Orden del código
