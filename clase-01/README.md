## Git

## Cambiar el nombre por defecto de la rama principal

```sh
git config --global init-defaultBranch main
```

## Estados de los archivos en un repositorio de GIT

* Untracked (Sin seguimiento) => archivos que no se agregaron al index/stage y por consecuente no se les da seguimiento.
* Staged => Archivos que fueron agregados al index/stage area y cuyos cambios van a ser incorporados al repositorio
* Unmodified => Archivos que se cuentran en en el respositorio y no fueron modificado (Con respecto al repositorio)
* Modified => Archivos que se encuentro en el repositorio pero difieren con lo que se encuentra actualmente en el directorio trabajo (Working directory)

## Areas posibles en las que pueden estar los archivos

* Working Directory (Directorio de trabajo) donde se van agregando y borrando archivos en desarrolllos

* Staging Area (Area de control de cambios) Se agregan los archivos para darle seguimiento y posteriormente sacarles una foto (commit)

* Local Repo (Area de validación de cambios, donde se registran las modificaciones realizadas) Donde van a estar todas las fotos (commit) que vaya sacando.


## Agrego en el staging area archivo (Area de confirmación)

```sh
git add <nombre-archivo>
git add clase-01/README.md
```