# ProjetoIntegrador_FrontEnd
Projeto desenvolvido em sala de aula usando React.js 
# BAIXAR E INSTALAR O NODE.JS
(https://nodejs.org/en/download/)

# TUTORIAL DE COMO INSTALAR O GERENCIADOR DE PACOTES E O NODE/REACT
```npm install --global yarn```

# CASO OCORRA ALGUM ERRO(OCORRE COM FREQUÊNCIA)
As vezes o windows impede que os comandos do yarn sejam executados. Para isso entre no Windows PowerShell como administrador e rode os seguintes comandos de uma vez...

```Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted```

Em teoria, isso é o suficiente para os scripts yarn executarem

## Configurando a ferramenta Git
`NOTA:` Tudo que está entre tags, deve ser substítuido pelos itens respectivos, dentro das mesmas. Utilize o Git Bash para as configurações.
Para as configurações iniciais execute:
  Comandos usados para indentificar os participantes na hora de um commit
  
```git config --global user.name "<nome do usuário>"```

```git config --global user.email <email do GitHub>```

### Pegando a chave SSH:
`NOTA:` Essa chave deve ser copiada no início ao fim (até o seu email) e deve ser colada no [SSH and GPG keys](https://github.com/settings/ssh/new) do GitHub

```cat ~/.ssh/id_rsa.pub```

### Inicializando o agente SSH:
```eval `ssh-agent -s` ```

```ssh-add ~/.ssh/id_rsa```

## Pronto está tudo configurado!!

Agora para clonar o repositório cole no terminal:

```git clone git@github.com:iagosasaki/ProjetoIntegrador_FrontEnd.git```

Na pasta do repositório clonado apenas digite `yarn` e ele irá fazer a instalação de todas as dependências 
