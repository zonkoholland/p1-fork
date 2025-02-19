# Práctica 1

Un repositorio para empezar a usar [git](https://git-scm.com/) y Github

## ¿Como probar en la nube?

[Github-Codespaces](https://github.com/features/codespaces)

## Comandos git básicos

```
git clone https://github.com/gitt-3-pat/p1
git status
git add .
git commit -m "TU MENSAJE"
git push

git checkout -b feature/1
git checkout main
```

## ¿Cómo escribir un README.md con formato?

[Github Markdown](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

# Práctica 1 - Marco Holland

## Documentos de entrega a la práctica

[Git.pdf](https://github.com/zonkoholland/p1-fork/blob/documentos/Git.pdf)
[entorno.pdf](https://github.com/zonkoholland/p1-fork/blob/documentos/entorno.pdf)


## git clone

Clonado del repositorio p1-fork a local:

![git_clone image](photos/git_clone.png)

## git add; git commit

Se utilizan estos comandos para añadir y hacer `commit` de la captura previa:

![git_clone image](photos/git_add_commit.png)

## git checkout

Este comando (junto con el prefijo -b) se utiliza para crear una nueva rama, el cuál se va a usar para almacenar los documentos:

```
C:\Users\holla\Documents\ICAI\AAA Tercero\Programación de Aplicaciones Telemáticas\GitHub\p1-fork>git checkout -b documentos
Switched to a new branch 'documentos'

C:\Users\holla\Documents\ICAI\AAA Tercero\Programación de Aplicaciones Telemáticas\GitHub\p1-fork>git branch
* documentos
  main
```

## git status

Se muestran los cambios listos para hacer `commit`:
 
![git_clone image](photos/git_status.png)

## git push

Se empujan los cambios guardados, actualizándose en remoto:

```
C:\Users\holla\Documents\ICAI\AAA Tercero\Programación de Aplicaciones Telemáticas\GitHub\p1-fork>git branch
* documentos
  main

C:\Users\holla\Documents\ICAI\AAA Tercero\Programación de Aplicaciones Telemáticas\GitHub\p1-fork>git push
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 140.18 KiB | 11.68 MiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/zonkoholland/p1-fork.git
   b9821a7..28907f8  documentos -> documentos

C:\Users\holla\Documents\ICAI\AAA Tercero\Programación de Aplicaciones Telemáticas\GitHub\p1-fork>
```


