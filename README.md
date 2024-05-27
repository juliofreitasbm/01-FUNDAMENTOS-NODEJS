# Módulo 1 de NodeJS Rocket-Seat

Esse módulo possui a estruturação de um projeto NodeJS com fundamentos de backend procurando utilizar sempre que possível funções nativas e evitando frameworks.

___
### Palavras chave:
>Node, NPM, HTTPie, Insomnia, GET, POST, PUT, DELETE, Buffers, Streams, Json, UUID, Routes, Regex

## Principais comandos:

### Guia: "Instalando o Node e o NPM"

+ `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash` : Instalando o nvm.
+ `nvm -v` : Verificando versão do nvm instalada.
+ `nvm install --lts`: Instalando a versão estável mais recente do node.js.
+ `node -v` : Verificando versão do node instalada.
  >Caso esse comando retorne uma versão antiga utilize `nvm use --lts` para utilizar a versão mais recente do node.

### Guia: "Instalando HTTPie" para Fedora

+ `dnf install httpie` : Instalar o httpie
+ `dnf upgrade httpie` : Faz o upgrade do httpie

### Aula "node --watch"

+ `"dev": "node --watch src/server.js"`: Script para rodar o projeto e recarregá-lo automaticamente ao salvar as alterações.

+ `http localhost:3333` : Comando para fazer um GET com httpie.
  >Colocando POST, PUT ou DELETE após o http é possível mudar o tipo da requisição.

### Aula "Corpo da requisição em JSON (Stream & Buffers)"

+ Instalando Insomnia no Fedora com "snap"
  ```
    sudo dnf install snapd
    sudo ln -s /var/lib/snapd/snap /snap
    sudo snap install insomnia
  ```