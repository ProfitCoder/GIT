# Git from Scratch 🌿

Repository created during my second year of **Web Application Development (DAW)** to learn Git and version control.

## 📚 Basic Git Commands

### Check the installed Git version

```bash
git --version
```

Displays the version of Git installed on the computer.

### Create a Git repository

```bash
git init
```

Initializes a new Git repository by creating a hidden `.git` directory.

### Check the repository status

```bash
git status
```

Shows modified, staged and untracked files.

### Add files to the staging area

```bash
git add filename
```

Adds a specific file to the staging area.

```bash
git add .
```

Adds all modified and new files to the staging area.

### Create a commit

```bash
git commit -m "Description of the changes"
```

Creates a commit with the staged changes and an explanatory message.

### Display commit information

```bash
git show
```

Displays detailed information about the latest commit and its changes.

### Restore a file

```bash
git restore filename
```

Discards changes made to a file that has not been committed.

### Change branch or restore an old version

```bash
git checkout branch-name
```

Changes from the current branch to another branch.

```bash
git checkout commit-hash
```

Temporarily displays the project as it existed in a specific commit.

### Reset the repository

```bash
git reset --hard commit-hash
```

Returns the repository to a specific commit and deletes subsequent local changes.

> ⚠️ Warning: `git reset --hard` permanently discards uncommitted changes. Use it carefully.

## 🎯 Purpose

The purpose of this repository is to practise the basic Git workflow, understand version control and document the commands learned during the course.

## 📌 Project Status

🟡 **Work in progress**

This repository will be updated as I learn new Git commands and concepts.

---

# Git desde cero 🌿

Repositorio creado durante mi segundo curso de **Desarrollo de Aplicaciones Web (DAW)** para aprender Git y el control de versiones.

## 📚 Comandos básicos de Git

### Comprobar la versión instalada

```bash
git --version
```

Muestra la versión de Git instalada en el equipo.

### Crear un repositorio Git

```bash
git init
```

Inicializa un repositorio Git creando una carpeta oculta llamada `.git`.

### Consultar el estado del repositorio

```bash
git status
```

Muestra los archivos modificados, preparados y todavía no controlados por Git.

### Añadir archivos al área de preparación

```bash
git add nombre-archivo
```

Añade un archivo concreto al área de preparación.

```bash
git add .
```

Añade todos los archivos nuevos y modificados al área de preparación.

### Crear un commit

```bash
git commit -m "Descripción de los cambios"
```

Crea un commit con los cambios preparados y un mensaje explicativo.

### Mostrar información de un commit

```bash
git show
```

Muestra información detallada sobre el último commit y sus cambios.

### Restaurar un archivo

```bash
git restore nombre-archivo
```

Descarta los cambios realizados en un archivo que todavía no se han confirmado.

### Cambiar de rama o consultar una versión anterior

```bash
git checkout nombre-rama
```

Cambia de la rama actual a otra rama.

```bash
git checkout hash-del-commit
```

Permite consultar temporalmente el estado del proyecto en un commit concreto.

### Restablecer el repositorio

```bash
git reset --hard hash-del-commit
```

Devuelve el repositorio a un commit concreto y elimina los cambios locales posteriores.

> ⚠️ Aviso: `git reset --hard` elimina los cambios no confirmados de manera permanente. Debe utilizarse con precaución.

## 🎯 Objetivo

El objetivo de este repositorio es practicar el funcionamiento básico de Git, comprender el control de versiones y documentar los comandos aprendidos durante el curso.

## 📌 Estado del proyecto

🟡 **En desarrollo**

Este repositorio se actualizará conforme aprenda nuevos comandos y conceptos de Git.
