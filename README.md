# SRE Challenge

## Sobre o Desafio: 

Esse é um teste feito para conhecer um pouco mais de cada candidato. Não é um teste objetivo e não há apenas uma solução que consideramos correta, o intuito é ser um estudo de caso com o propósito de conhecer o seu modo de trabalhar.

## Introdução

Temos neste repositório uma aplicação em Kotlin simples com uma API REST que responde um Hello World quando recebe um GET na porta 8080. (ex: curl http://localhost:8080/)

## A primeira parte do desafio: 

* Crie um diretório com nome de "parte1" e faça esses steps dentro dele.
    * Containerize essa aplicação
    * Crie um Helm chart contendo todos os componentes necessários para essa aplicação rodar em um cluster de Kubernetes

## A segunda parte do desafio:

* Crie um diretório com nome de "parte2" e faça esses steps dentro dele.
    * Provisione uma infraestrutura na AWS com terraform para subir essa aplicação containerizada
    * Lembre-se de utilizar EC2, ELB, ASG entre outros serviços da AWS 

## Final
* Crie um pipeline com Github Actions que realize o build e o deploy da infraestrutura e da aplicação em um cluster EKS.

## Alguma dicas importantes:
* Utilize o free tier da AWS para não ter nenhum custo desnecessário.
* Qualidade da documentacão
* Utilizar boas práticas
* Organização do código
* Ser eficiente e simples

## Entrega do desafio:
Por fim, compacte todo o código e nos envie.

 **Versão do Gradle: 4.10**
