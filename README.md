# Snippets para Git

## Índice de contenidos

- [Crear repositorio](#crear-repositorio)
- [Comprobar versión Git](#comprobar-version-git)
- [Clonar repositorio](#clonar-repositorio)
- [Publicar web con GitHub Pages](#publicar-web-con-github-pages)
- [Transferir repositorio de Bitbucket a Github](#transferir-repositorio-de-bitbucket-a-github)
- [Configurar usuario repositorio](#configurar-usuario-repositorio)


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

## Transferir repositorio de Bitbucket a Github

```
cd $HOME/directoriodelrepositorio
$ git remote rename origin bitbucket
$ git remote add origin rutadelrepositorioengithub
$ git push origin master
$ git remote rm bitbucket
```

## Configurar usuario repositorio

Configuración global del usuario:
```
$ git config --global user.name "Nombre del usuario"
$ git config --global user.email "correo@ejemplo.es"
```

Configuración para un respositorio específico:
```
$ git config user.name "Nombre del usuario"
$ git config user.email "correo@ejemplo.es"
cat .git/config
```
