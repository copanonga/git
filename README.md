# Snippets para Git

## Índice de contenidos

- [Crear repositorio](#crear-repositorio)
- [Comprobar versión Git](#comprobar-version-git)
- [Clonar repositorio](#clonar-repositorio)
- [Publicar web con GitHub Pages](#publicar-web-con-github-pages)
- [Transferir repositorio de Bitbucket a Github](#transferir-repositorio-de-bitbucket-a-github)


## Crear repositorio

```
echo "# Título" >> README.md
git init
git add .
git commit -m "Primer commit"
git remote add origin url...
git remote -v
git push -u origin master
```

## Comprobar versión Git

```
git --version
```

## Clonar repositorio

```
git clone urlRepositorio...
```

## Publicar web con GitHub Pages

```
 - Crear repositorio
 - Ir a Settings y habilitar GitHub Pages en master
 
  El sitio se publicará en username.github.io/nombredelrepositoriocreado

```

Transferir repositorio de Bitbucket a Github

```
cd $HOME/directoriodelrepositorio
$ git remote rename origin bitbucket
$ git remote add origin rutadelrepositorioengit
$ git push origin master
$ git remote rm bitbucket
```
