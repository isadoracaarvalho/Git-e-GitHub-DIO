# Enviando e baixando alterações com repositório remoto

## Como enviar alterações?

1. Connectar os dois repositórios
```
git remote add origin URL
```

2. Caso o trabalho esteja sendo feito na branch master
```
git branch -M main
```

3. Envia as informações do repositório local para o repositório remoto
```
git push -u origin main
```

## Como baixar alterações?

1. Puxa as alterações do repositório remoto para o local
```
git pull
```