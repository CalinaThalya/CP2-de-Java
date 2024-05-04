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

## Diagrama UML:

![Diagrama UML](https://github.com/CalinaThalya/CP2-de-Java/assets/116985483/85e6e6a9-cd84-43de-b0d7-c2b85d8a78f5)

## Endpoints :

```JAVA
{
    "endpoints": [
        {
            "method": "GET",
            "path": "/brinquedos",
            "description": "Retorna uma lista de todos os brinquedos."
        },
        {
            "method": "GET",
            "path": "/brinquedos/{id}",
            "description": "Retorna os detalhes de um brinquedo específico com o ID fornecido."
        },
        {
            "method": "POST",
            "path": "/brinquedos",
            "description": "Cria um novo brinquedo com base nos dados fornecidos no corpo da requisição."
        },
        {
            "method": "DELETE",
            "path": "/brinquedos/{id}",
            "description": "Deleta o brinquedo com o ID fornecido."
        },
        {
            "method": "PUT",
            "path": "/brinquedos/{id}",
            "description": "Atualiza as informações de um brinquedo existente com o ID fornecido, utilizando os dados fornecidos no corpo da requisição."
        }
    ]
}

```

## Foi feita a criação das tabelas no banco de dados e inseridos os seguintes codigos:
![Dados inseridos na tabela](https://github.com/CalinaThalya/CP2-de-Java/assets/116985483/df8f3dab-9497-4c31-b27d-63080ee42e76)

## Testes:
Para testar os endpoints, foi utilizado o software Postman. Segue o resultado de um dos testes:

![Postman metodo GET](https://github.com/CalinaThalya/CP2-de-Java/assets/116985483/a1aa62d2-6f27-461d-b3c8-430916e3b03f)


