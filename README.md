Se hicieron los pasos como se especifica en el taller.

- se creo un repositorio en GitHub, ya tenia una cuenta existente
- se  configuro el nombre
- se hizo la creación de la rama feature, desde la rama master
- agrege el archivo txt y realice el commit
- cambie a la rama master
- hice reste para deshacer el ultimo commit en master
- realice la creación de la rama hotfix, hice el respectivo commit
- aplique Cherry.pick Esto trajo el cambio del commit en hotfix a master sin fusionar ramas completas.
- hice la creación de un conflicto en la rama feature

Esto genera un conflicto al intentar fusionar las dos ramas, ya que ambas contienen cambios distintos en un archivo con el mismo nombre.

Se produjo un conflicto en el archivo comflicto.txt (indicado por el mensaje Merge conflict in comflicto.txt). fue necesario resolver manualmente el conflicto y realizar un commit para completar la fusión.
