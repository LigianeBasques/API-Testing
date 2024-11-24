# 🏨API Restful-booker🏨 #

# 👀Visão Geral👀 #
É uma API do Restful-Booker, um sistema de reservas de um hotel

# 🔨 Estrutura dos testes da API🔨  #
+ **Restful-booker:** CRUD (Create, Read, Put, Delete) para gerenciar informações sobre reservas em um hotel, como criar uma reserva, buscar uma reserva especifica, listar todas as reservas, atualizar as reservas e deletar uma reserva, filtar por nome, filtrar por check in ou checkout e gerar token.
+ **Endpoints comuns:**
+ POST {{baseURL}}/booking
+ GET {{baseURL}}/booking/{{id}}
+ PUT {{baseURL}}/booking/1
+ DELETE {{baseURL}}/booking/2


# 🎯Configuração do ambiente de testes #
Antes de realizar os testes na API configurei o ambiente de testes, com algumas variáveis específicas para que fosse usadas nas requisições.

**Ambiente de testes**
![Ambiente de teste](https://imgur.com/RoaNmv7.png)

# 📈Testando a API no Postman📈 #
No Postman foi adicionado a collection da API restful-booker, além de realizar os testes de CRUD, também realizei algumas validações, como por exemplo: Status code 200, tempo de resposta, campos obrigatórios, formato da datas entre outros. 

### ✅Autenticação ###
**Gerar token de autenticação**
![Token de autenticação](https://imgur.com/k6tYcjq.png)

**Tentar gerar token com credenciais inválidas**
![Credencial inválidao](https://imgur.com/nEYTqTZ.png)

### 🔎Resultados dos Testes ###
**Gerar token de autenticação**
![Resultado testes](https://imgur.com/CJsRYpO.png)

**Tentar gerar token com credenciais inválidas**
![Resultado testes](https://imgur.com/pBUH6iG.png)

### 📁Gestão de reservas ###

**Criar uma nova reserva**
![Criar uma nova reserva](https://imgur.com/qR8UEYz.png)

### 🔎Resultados dos Testes ###
**Criar uma nova reserva**
![Criar uma nova reserva](https://imgur.com/Q1tUJND.png)

**Buscar uma reserva específica**
![Busca reserva id](https://imgur.com/cVeUaxq.png)

### 🔎Resultados dos Testes ###
**Buscar uma reserva específica**
![Busca reserva id](https://imgur.com/GXHDz1u.png)

**Listar todas as reservas**
![Lista todas a reservas](https://imgur.com/a0MC63q.png)
### 🔎Resultados dos Testes ###
**Listar todas as reservas**
![Lista todas a reservas](https://imgur.com/TufVamf.png)

**Atualizar uma reserva existente**
+ **Antes de atualizar dado**
![Atualizar reserva](https://imgur.com/WJ3UcEE.png)

+ **Dado atualizado**
![Atualizar reserva](https://imgur.com/LgRLUdj.png)

### 🔎Resultados dos Testes ###
**Atualizar uma reserva existente**
![Atualizar reserva](https://imgur.com/1dpFZnh.png)

**Deletar uma reserva**
![Deletar reserva](https://imgur.com/O3Z0L3b.png)

### 📋 Filtros e buscas: ###
**Buscar reservas por nome**
![Busca nome](https://imgur.com/bQ7ITP2.png)


**Buscar reservas por data de check-in e por data de check-out**
![Busca checkin e checkout](https://imgur.com/46vlKay.png)
