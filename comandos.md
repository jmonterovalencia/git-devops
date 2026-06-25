

# Prueba de comandos básicos:

# git config (configurar el usuario)
```bash
git config --global user.name "Jose Pedro Montero Valencia"
git config --global user.email "josepedromontero@hotmail.com"
```

## git branch (listar ramas)
```bash
git branch
* main
```

## git branch (crear una nueva rama a partir de la actual)
```bash
git branch feature/comandos-basicos
```

## git switch (cambiar a la nueva rama)
```bash
git switch feature/comandos-basicos
  Switched to branch 'feature/comandos-basicos'
```

## git branch (listar ramas)
```bash
git branch
* feature/comandos-basicos
  main
```

## git status (muestra el estado actual del repo, con ficheros modificados, añadidos y/o eliminados)
```bash
git status
  On branch feature/comandos-basicos
  Untracked files:
    (use "git add <file>..." to include in what will be committed)
        comandos.md

  nothing added to commit but untracked files present (use "git add" to track)
```

## git log -oneline (comprobar el historial de commits)
```bash
git log --oneline
  7abeebb (HEAD -> feature/comandos-basicos, origin/main, origin/HEAD, main) Update README.md
  6a9d91d Initial commit
```

## git add (añadir ficheros al staging)
```bash
git add .
```

## git commit (registrar los cambios en el historial del repo)
```bash
git commit -m "Se añade este fichero al repo"
  [feature/comandos-basicos f61a25f] Se añade este fichero al repo
   1 file changed, 62 insertions(+)
   create mode 100644 comandos.md
```

## git fetch origin (sincronizar con el repo remoto, descarga actualizaciones)
```bash
git fetch origin
```

## git push --force origin main (carga el stage en el repo remoto y modifica historial)
```bash
git push --force origin main


```
