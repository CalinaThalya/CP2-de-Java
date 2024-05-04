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

![image (2)](https://github.com/CalinaThalya/CP2-de-Java/assets/116985483/a1c457b2-3cae-4616-8cf9-580da3d6285e)




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
Para testar os endpoints, foi utilizado o software Postman. Seguem o resultado de um dos testes:



![Postman metodo GET](https://github.com/CalinaThalya/CP2-de-Java/assets/116985483/a1aa62d2-6f27-461d-b3c8-430916e3b03f)





