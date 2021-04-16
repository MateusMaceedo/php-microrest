<h1 align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/PHP-logo.svg/1200px-PHP-logo.svg.png" width="122" height="75">
 <br>
</h1>

#### O que é REST API?
REST significa Representational State Transfer e significa que a solicitação e a resposta devem conter uma representação das informações, ou seja, devem estar em um determinado formato. Então, basicamente, as solicitações devem usar métodos HTTP adequados e a resposta deve estar em um formato adequado, como JSON ou XML, em vez de texto simples.

A API REST nada mais é do que uma API normal com um conjunto de princípios. Precisamos seguir um conjunto de regras ao criar e consumir a API REST.

As regras incluem o seguinte.

1. Use métodos HTTP apropriados ao realizar chamadas de API. A seguir estão os quatro métodos HTTP principais que devem ser usados ​​para enviar e receber solicitações de API.
uma. GET - Para ler registros únicos ou múltiplos.
b. POST - Para criar um novo registro.
c. PUT - Para atualizar um registro.
d. DELETE - Para excluir um registro.

2. Use a hierarquia de URL adequada em vez de usar string de consulta de URL para URLs de API.
uma. Bom - http://example.com/api/products/1
b. Ruim - http://example.com/api/products.php?id=1

3. Evite usar verbos como nomes de recursos na URL da API e, em vez disso, use substantivos e métodos HTTP adequados.
uma. Bom –http: //example.com/api/products
b. Ruim –http: //example.com/api/products/add

4. Use plurais para os nomes dos recursos no URL da API.
uma. Bom –http: //example.com/api/products
b. Ruim –http: //example.com/api/product

5. Use os códigos de resposta HTTP para indicar o status das solicitações.
6. Os dados de resposta devem estar no formato JSON ou XML.

<h1 align="center">
<img width="696" height="288" src="https://apptha-blog.s3.amazonaws.com/blog/wp-content/uploads/2015/11/API-Using-PHP.jpg" class="attachment-post-thumbnail wp-post-image" alt="API usando PHP" title="API usando PHP">
</h1>

#### Links de apoio:
- [apptha](https://www.apptha.com/blog/how-to-build-a-rest-api-using-php/)
- [Introdução a JSON e PHP (Webservices)](http://blog.thiagobelem.net/introducao-a-json-e-php-webservices)
- [Laravel 4: A Start at a RESTful API (Updated)](https://code.tutsplus.com/tutorials/laravel-4-a-start-at-a-restful-api-updated--net-29785)
- [Create Your Own XML/JSON/HTML API with PHP](https://dzone.com/articles/create-your-own-xmljsonhtml)

#### Desafios:
[Php Developer JR](https://gist.github.com/henriquebelfort/9f87aaad1c26b3b23a3bdcb9d6c995e2)
