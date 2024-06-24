# Módulo 1 de NodeJS Rocket-Seat

Esse módulo possui a estruturação de um projeto NodeJS com fundamentos de backend procurando utilizar sempre que possível funções nativas e evitando frameworks.

___
### Palavras chave:
>Node, NPM, HTTPie, Insomnia, GET, POST, PUT, DELETE, Buffers, Streams, Json, UUID, Routes, Regex

## Conteúdo Programático do Módulo 1:

<details style="font-size: 16px">
<summary><strong style="font-size: 18px">1. Iniciando com Node.js</strong></summary>

  ---

  + Introdução
  + Criando um projeto Node.js
  + node --watch

  ---
</details>

<details style="font-size: 16px">
<summary><strong style="font-size: 18px">2. Estrutura da aplicação</strong></summary>

  ---

  + Rotas de criação e listagem (Métodos HTTP)
  + Salvando usuários em memória (Headers)
  + Conhecendo HTTP status codes

  ---
</details>

<details style="font-size: 16px">
<summary><strong style="font-size: 18px">3. Streams no Node.js</strong></summary>

  ---

  + Entendendo Streams no Node
  + Criando stream de leitura
  + Stream de escrita e transformação
  + Aplicando Streams no módulo HTTP
  + Consumindo uma stream completa
  + Corpo da requisição em JSON (Stream & Buffers)
  + Entendendo Buffers no Node
  + Criando middleware de JSON

  ---
</details>

<details style="font-size: 16px">
<summary><strong style="font-size: 18px">4. Banco de dados</strong></summary>

  ---

  + Criando banco de dados JSON
  + Persistindo banco de dados
  + Criando ID único e universal (UUID)

  ---
</details>

<details style="font-size: 16px">
<summary><strong style="font-size: 18px">5. Rotas da aplicação</strong></summary>

  ---

  + Separando rotas da aplicação
  + Route e Query parameters
  + Criando regex dos parâmetros
  + Rotas com parâmetros (RegEx)
  + Remoção de registros
  + Atualização de registros
  + Capturando query parameters
  + Filtrando lista do banco de dados

  ---
</details>

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