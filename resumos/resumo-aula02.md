# CRIANDO E CLONANDO REPOSITÓRIOS

Existem duas maneiras de criar um repositório local

## 1 - Transformar um diretório local que não esta sob controle de versão, num repositório Git:

Tutorial e comandos úteis

1. criar uma pasta que sera transformada no repositório Git
```
mkdir nome-da-pasta
```
2. Comandos para acessar repositório e arquivos
```
cd nome-da-pasta/

cd .git
```

3. Cria repositório localmente
```
git init
```

4. Exibe conteúdo
```
cat config
```

5. Para conectar um repositório local a um repositório remoto
```
git remote add origin URL
```

## 2 - Clonar um repositório Git existente:

Tutorial e comendos úteis

1. Clonar um repositório ja existente
```
git clone url
```

2. Para alterar o nome do diretório que sera clonado localmente
```
git clone url novo-nome
```

3. Para ver com quais repositórios remotos está conectado
```
git remote -v
```

## 👩‍💻 Mais alguns comandos úteis

- listar os arquivos da pasta
```
ls
```

- Verifica o status 
```
git status
```

- Cria um arquivo
```
touch nome.tipo (README.md)
```

- Mostra histórico de versões
```
git log
```