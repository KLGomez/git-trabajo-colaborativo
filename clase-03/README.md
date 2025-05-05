# Clase 03 - Git desarrollo Colaborativo

## Repaso de fusiones

## git merge (fusionar ramas)

```sh
git merge <nombre-rama>
```
* Merge automatico (Fast-forward)
Consiste en un merge sin conflictos
* Merge con commit (Con commit)
Consiste en un merge con commit cuando hay conflictos pero se resuelve mediante nano el commit y el merge se realiza
* Merge con conflicto (Conflict)
Consiste en un merge con conflicto y se resuelve manualmente 

## Detener el proceso de fusion de ramas

```sh
git merge --abort
```

## Git log extendido

```sh
git log --oneline --decorate
git log --oneline --decorate --graph
```

## Git log por rama

```sh
git log <rama>
```

## Git log por autor

```sh
git log --author=<autor>
```

