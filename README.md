# SISTEMA-DE-GESTION-DE-BIBLIOTECAS

El proyecto del sistema de gestión de bibliotecas es un codigo que permite almacenar
varios tipos de libros tanto fisicos como digitales permite ingresar el nombre del
libor, el autor, el año de publicación, el formato fisico o digital, el número de paginas
ademas el proyecto posee controladores de posibles errores como entrada de datos no
numericos para el año de publicacion y el número de paginas.

# COMO EJECUTAR EL PROGRAMA

# En esta parte debe ingresar el titulo del libro el nombre del autor y el año de publicación
a=Libro("El valle", "Luis Gomez", 2025) 
# En esta parte debe ingresar el titulo del libro el nombre del autor, el año de publicacion y el formato
b=LibroDigital("El Principito", "Antoine de Saint-Exupéry", 1943, "PDF")
# En esta parte debe ingresar el titulo del libro y nombre del autor y año de publicación numero de paginas
c=LibroFisico("Cien años de soledad", "Gabriel García Márquez", 1967, 417)
# Esta parte llama a la clase Bibloteca
d=Biblioteca()
# Esta parte llama a la función agregar_libro y agrega el contenido que contiene la variable a.
d.agregar_libro(a)
# Esta parte llama a la función agregar_libro y agrega el contenido que contiene la variable b.
d.agregar_libro(b)
# Esta parte llama a la función agregar_libro y agrega el contenido que contiene la variable c.
d.agregar_libro(c)
# Esta parte llama a la función mostrar libro y muestra todos los libros que hay.
d.mostrar_libros()

# REFLECCIÓN SOBRE LAS VENTAJAS DE USAR SUPER() EN ESTE SISTEMA

las ventajas de usar SUPER() esque nos ayuda mucho al momento de utilizar
erencias en un proyecto ya que nos ahorran muchas lineas de códogo ya que
no nesesitamos volver a declarar los atributos que vamos a usar.
