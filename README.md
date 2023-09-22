# pratica-16

Criar um programa que declare um array contendo 5 objetos representando países, sendo que cada país deve ter os seguintes atributos: nome e população.
Persistir os objetos do array no banco de dados devweb2 no mongoDB na coleção países.
No mesmo projeto, criar um servidor web Express com a rota /paises utilizando o verbo GET. Nessa rota deve ser passado o parâmetro populacao via query.
Caso o parâmetro não seja informado ou não seja um número, a rota deve retornar um status 400 com uma mensagem orientativa.
Caso o parâmetro seja informado, a rota deverá conectar ao mongoDB e recuperar todos os países que tem a população maior ou igual ao parâmetro informado. A resposta da rota deverá ser um array json de países.
