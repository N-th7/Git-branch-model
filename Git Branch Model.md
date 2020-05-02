# Git Branch Model
El GIT BRANCH MODEL es un flujo de trabajo el cual se basa en ser centralizado y a la vez no. Cuando trabajamos con este flujo tenemos un repositorio central el cual es el principal. Este repositorio es el **ORIGIN** el cual es un repositiro remoto.

Cada desarrollador que es parte del proyecto va descargando el repositorio o tambien lo actualiza dependiendo los requerimientos.

## Ramas principales
Al trabajan con este flujo tenemos dos ramas las cuales son las principales en el trabajo y estas son:

- Master
- Developer

Estas dos ramas se encuentran en el repositorio remoto y tienen una vida infinita.
En la rama del developer realizamos todo el desarrollo del proyecto y cuando ya esta listo para ser actualizado a la rama master creamos una rama secundaria la cual sere la rama **RELEASE** y esta sera por asi decirlo la nueva vercion del proyecto. Hacemos merge en la rama developer.

## Ramas secundarias

Estas ramas secundarios o de apoyo, nos ayudan en el momento que se presentan errores, tenemos que hacer nuevas caracteristicas, etc. A diferencia de las ramas principales estas tienen un tiempo limitado de vida.

Las distintas ramas que tenemos en este sector son:

- Features
- Release
- Hotfix

Cada una de estas ramas tiene una funcion en especifico, y estan categorizadas por los usos que nosotros vayamos a darle. Cada una de estas tiene un tiempo de vida limitado porque cuando cumplen su funcion dejan de ser utilizadas.

El model de ramas funciona de manera que no trabajamos solo con ramas grandes, sino trabajamos con un conjunto de ramas las cuales tienen funciones y tareas especificas, las cuales vamos creando cuando las requerimos.
