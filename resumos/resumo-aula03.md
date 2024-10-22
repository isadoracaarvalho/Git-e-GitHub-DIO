# Salvando/Desfazendo alterações no repositório local

## Salvando alterações no repositório local

- Para adicionar um arquivo específico
```
git add nome-do-arquivo
```

- Para adicionar todos os arquivos
```
git add .
```

- Commitar mudanças
```
git commit -m"Essa alteração foi feita"
```

## Desfazendo alterações no repositório local

- Desfazer git init (apaga o repositório por inteiro)
```
rm -rf .git
```

- Recupera um arquivo que foi apagado (descarta todas as alterações locais)
```
git restore nome-do-arquivo
```

- Altera o último commit
```
git commit --amend -m"nova mensagem"
```

- Desfaz o ultimo commit
```
git reset --soft rest-do-commit
``` 
```
git reset --mixed rest-do-commit
```
```
git reset --hard rest-do-commit
```

- 
```

```