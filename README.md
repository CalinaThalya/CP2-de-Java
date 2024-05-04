# Relatório - Loja Toy

## Descrição do Projeto : 
Este projeto consiste em um aplicativo desenvolvido em Java usando o framework Spring Boot, configurado com o Maven. O objetivo do aplicativo é fornecer um sistema de gerenciamento de brinquedos para uma empresa voltada para crianças até 12 anos. O aplicativo permite a realização de operações CRUD (Create, Read, Update, Delete) para manipulação dos dados de brinquedos em um banco de dados Oracle.

## Tecnologias Utilizadas:
- Java
- Spring Boot
- Maven
- Oracle Database
- Postman

## Spring Initializr:

![image](https://github.com/CalinaThalya/cp2-java/assets/116985483/3929b58d-cbb4-457a-b420-e09760bd52ab)



## Estrutura do Projeto
- src/main/java: Contém os pacotes e classes Java do projeto.
- src/main/resources: Contém os arquivos de configuração.
- META-INF: Contém o arquivo persistence.xml com as configurações de conexão com o banco de dados Oracle.


## Endpoints :

- POST /brinquedos: Cria um novo brinquedo com os dados fornecidos no corpo da requisição.
- GET /brinquedos: Retorna informações sobre todos os brinquedos cadastrados.
- GET /brinquedos/{id}: Retorna informações sobre um brinquedo específico com o ID fornecido.
- PUT /brinquedos/{id}: Atualiza as informações de um brinquedo específico com o ID fornecido.
- DELETE /brinquedos/{id}: Remove um brinquedo específico com o ID fornecido.

## Testes:
Para testar os endpoints, foi utilizado o software Postman. Seguem os resultados dos testes:

