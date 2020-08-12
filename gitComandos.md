## Comandos do Git

- Configurar usuário git
```
git config --global user.name "exemplo" || git config --global user.email "examplo@examplo.com"
```

- Inicializar um repositório git
```
git init
```

- Visualizar estado dos arquivos do diretório git
```
git status
```

- Adicionar arquivos para commit
´´´
git add <nome arquivo> || git add .
´´´

- Realizar o commit
```
git commit -m "mensagem"
```

- Ver histórico de commits
```
git log || git log --oneline || git log -p || git log --graph
```

- Adicionando repositórios remotos no projeto
```
git remote add <nome servidor> <caminho do servidor>
```

- Clonando repositório remoto
```
git clone <caminho do servidor> 
```

- Renomear nome servidor
```
git remote rename <nome atual> <novo nome>
```

- Enviar arquivos locais para servidor 
```
git push <nome servidor> <branch>
```

- Pegar arquivos do servidor
```
git pull <nome servidor> <branch>
```

- Criar branch
```
git branch <nome da branch> || git checkout -b <nome da branch>
```

- Mudar para uma branch
```
git checkout <nome da branch>
```

- Juntar conteúdos de dois branchs em um novo commit
```
on master
git merge <nome da branch>
```

- Juntar conteúdos de dois branchs sem um novo commit
```
on master
git rebase <nome da branch>
```