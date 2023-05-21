
CoderHouse

Curso: Python

Profesor: David Bustos Usta

Comisión: 40435

Alumna:Laura Flores

Video: https://youtu.be/9qrylg5bstg

Link al sitio web: lauflores.pythonanywhere.com

# Las Recetas de Lau

Este proyecto busca emular un sitio web de tipo blog, sobre recetas de cocina.
Dentro de este se puede hacer lo siguiente:

- Crear, editar, leer y borrar articulos.
- Crear un usuario que permite agregar los articulos a una Wish list.
- Dejar un comentario en referencia al sitio. 

# Observaciones:
Para tener el rango de owner y poder modificar, eliminar y crear productos, se debe ir al panel de localhost:8000/admin y cambiar el permiso para el perfil. (Entrar a AppFinal/Clients, ingresar al ultimo creado, y en rol cambiar de cliente a owner)

En la página principal (Home) se mencionan Las recetas del dia, estas aparecen siempre y cuando al crear o editar la receta se complete el articulo con un valor para highlight igual a 1. Esto se realiza con el fin de destacar alguna receta en particular, la cual se quiere recomendar a quien visita el sitio. 


# Instalacion 

El Software necesario se puede instalar de la siguiente manera:

## Primero verificar la version de Python
El presente proyecto fue escrito con Python 3.10.11, en base a eso se sugiere que se pruebe con esta version o superior con el fin de evitar posibles incompatibilidades.

Como puede confirmar la version de Python? 

` El comando de python puede variar segun el sistema operativo, por favor tener esto en cuenta. `

Mac os:

```bash
> python --version
> Python 3.10.11
```

in windows:

```bash
c:\> python3 --version
c:\> Python 3.10.11
```

## Instalar dependencias

Para instalar dependencias, se necesita ejecutar `pip install`, asegurase de estar dentro de la carpeta del archivo y poder visualizar el archivo `requirements.txt` cuando ejecute `ls` o en su defecto `dir`

```bash
> pip install -r requirements.txt
```
Se vera en la terminal como se va instalando el software requerido.

`Algunos sistemas operativos pueden requerir que utilice pip3 en lugar de pip `

## Configuracion de Django

Una vez terminada la instalacion de las dependencias, debera de ejecutar unos comandos de Django.

### Migraciones

Crear la base de datos
Mac os:
```bash
> python3 mananage.py migrate
```
windows:
```bash
c:\> python mananage.py migrate
```

### Crear Superuser
Mac os:
```bash
> python3 mananage.py createsuperuser
(Pedira usuario email y contraseña)
```
windows:
```bash
c:\> python mananage.py createsuperuser
(Pedira usuario email y contraseña)
```

### Ejecutar el servidor
Mac os
```bash
> python3 mananage.py runserver
```
windows:
```bash
c:\> python mananage.py runserver
```
