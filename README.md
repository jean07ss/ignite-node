# Ignite NodeJS

Repositorio com os códigos desenvolvidos durante as aulas do Ignite na RocketSeat

## Sobre o Node
O node é uma plataforma open-source que permite a execução de códigos JavaScript no backend./
Utiliza a v8 engine do Google para a execução de códigos JavaScript.

## Caracteristicas do Node
### `Baseado em Event Loop/Call Stack`
O node é baseado em uma estrutura de eventos que permite a execução de códigos de forma assíncrona.
O event loop é responsável por executar as funções que estão na call stack.
O event loop é single thread mas conforme ele pega as funções da call stack ele atribui a uma thread (por padrão 4 disponiveis).

### `Non-blocking I/O`
Diferente do Java e do PHP, não precisa que um metodo chamado antes seja concluido para chamar um novo método

### `Modulos proprios`
Possui modulos proprios que ja vem instalados (http, dns, fs, buffer e etc)

### `Frameworks`
Possui frameworks que ja vem instalados (express, socket.io, etc)
Mais famosos: Express, Egg.js, Nest.js, Adonis.js

## API
Application Programming Interface
Conjunto de funções que permitem a interação com o servidor

### REST
Represntation State Transfer
Modelo de arquituvo que permite a interação com o servidor

### `Client-server`
O cliente é separado do servidor e dessa forma ambos não precisam ter conhecimento sobre o que esta sendo executado

### `Stateless`
O cliente pode realizar varias requisicoes porem o servidor não armazena estados de uma requisição para outra

### `Cache`
A API deve ter suporte ao gerenciamento de cache

### `Interface Uniforme`
- Identificação dos recursos
Os recursos devem ser muito bem definidos, principalmente nas URLs
- Representação dos recursos
O servidor pode entregar as solicitações de várias formas
- Mensagens auto-descritivas
As mensagens de resposta devem ser muito bem descritas
- HATEOAS (Hypermedia as the Engine of Application State)
Poder retornar links dentro de uma requisição

### `Camadas`
Deve permitir camadas entre o Client e o Server, por exemplo, balanceamento de cargas

### `Código sob demanda`
Permite que as funcionalidades do cliente sejam extendidas na forma de script ou mini aplicações