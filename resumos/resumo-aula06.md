# TRABALHANDO COM BRANCHES - COMANDOS ÚTEIS NO DIA A DIA

- Faz o download dos objetos e refs do outro repositório
```
git fetch origin main
```

- Exibe as mudanças entre os commits, o commit, a árvore de trabalho, etc
```
git diff main origin/main
```

- Junte dois ou mais históricos de desenvolvimento
```
git merge origin/main
```

- Clona apenas uma das branches de um repositório remoto
```
git clone URL --branche nome-da-branche --single-branche
```

- Arquiva modificações e arquivos modificados
```
git stash
```

- Desarquiva modificações e arquivos modificados
```
git stach pop/apply
```