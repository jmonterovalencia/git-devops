

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

## git log -oneline
```bash
git log --oneline
  7abeebb (HEAD -> feature/comandos-basicos, origin/main, origin/HEAD, main) Update README.md
  6a9d91d Initial commit
```

## git add
```bash
git add .

```





