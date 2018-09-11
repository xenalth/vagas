# Escopo

Você possui uma empresa de pagamentos, e precisa implementar uma API através das quais seus clientes poderão manipular o cadastro de cartões de crédito. Os dados do cartão de crédito são estes abaixo:

|Campo|Descrição|
|---|---|
|number|Número do cartão|
|holder_name|O nome do dono do cartão|

Para facilitar o processo de integração, você precisa fornecer um SDK escrito em PHP, através do qual seus clientes possam realizar a integração de forma facilitada.

Assim, você deve:
* Implementar endpoints que façam as seguintes operações:
    * Cadastrar um cartão de crédito;
    * Atualizar um cartão de crédito;
    * Obter um cartão de crédito pelo seu ID;
    * Excluir um cartão de crédito.
* Implementar um SDK que facilitará o processo de integração nas operações acima.


# Requisitos:

* Não é necessário utilizar banco de dados, os dados da API poderão ser fake;
* Na API, utilizar um dos micro-frameworks abaixo:
    * [Flask](http://flask.pocoo.org/)
    * [Sinatra](http://sinatrarb.com/)
    * [Grape](https://github.com/ruby-grape/grape)
    * [Spark](https://spark.apache.org/)
    * [Slim](https://www.slimframework.com/)
* No SDK:
    * Não utilize cURL;
    * Escolha alguma biblioteca de integração HTTP, e justifique esta escolha no README do projeto;
    * Sua API terá autenticação no futuro, assim, seu SDK já deverá suportar o recebimento de um token de autenticação.


