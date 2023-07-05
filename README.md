<h1 align="center">Consulta de vendas</h1>

<p align='center'> 
    <img src="https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot"/>
    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/>  
</p>    
Sistema de vendas (Sale) e vendedores (Seller), onde o usuário informa opcionalmente, os dados e o sistema retorna uma listagem paginada com relatório de vendas contendo id, data, quantia vendida e nome do vendedor. 
<h2>Regras</h2>

- **Relatório de vendas**

  1. [IN] O usuário informa, opcionalmente, data inicial, data final e um trecho do nome do vendedor.

  2. [OUT] O sistema informa uma listagem paginada contendo id, data, quantia vendida e nome do
     vendedor, das vendas que se enquadrem nos dados informados.

     **Informações complementares**

     -  Se a data final não for informada, considerar a data atual do sistema. Para instanciar a data atual,

       utilize o comando:

     - Se a data inicial não for informada, considerar a data de 1 ano antes da data final. P

     - Se o nome não for informado, considerar o texto vazio.

     - Dica: receba todos os dados como String no controller, e faça os tratamentos

       

- **Sumário de vendas por vendedor**

  1. [IN] O usuário informa, opcionalmente, data inicial, data final.

  2. [OUT] O sistema informa uma listagem contendo nome do vendedor e soma de vendas deste vendedor
      no período informado.

    **Informações complementares:**

    -  As mesmas do caso de uso Relatório de vendas

<h2>Tecnologias utlizadas</h2>

- Java
- Springboot
- JPA
- Maven
- H2 Database
