# TRABALHANDO COM BRANCHES - CRIANDO, MESCLANDO, DELETANDO e TRATANDO CONFLITOS

## O que é uma Branche?

Uma Branche (em tradução, "Ramo") é uma ramificação do seu projeto.
- É um ponteiro móvel para um commit no histórico do repositório;
- Quando uma nova Branche é criada a partir de uma ja existente, a nova se inicia apontando para o mesmo commmit da Branch que estava quando foi criada.

## Criando uma nova Branche

```
git checkout -b nome-da-branche
```

- Lista o último commit de cada Branche
```
git branch -v
```

- Navega entre Branches
```

```

## Mesclando branches com a main
```
git merge nome-da-branche
```

## Excluindo Branches
```
git branc -d nome-da-branche
```

## Confitos de merge

Acontecem quando existem alterações concorrentes