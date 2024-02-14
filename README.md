## Desafio: Use Cases para a Entidade "Product"
### 1. Operações "create", "find", "list" e "update" para "Product"

Da mesma forma que fizemos a criação dos use cases realizando as operações: "create", "find", "list", "update" para "Customer", faça:

Crie as operações mencionadas acima para nossa entidade: "Product".
Implemente os **testes de unidade** e **integração** nos quatro use cases.


[Commit do desafio 1](https://github.com/lucasfreitass10/FullCycle3CleanArchitecture/commit/67d5233ea287b83feb00e9a64fd90b465d86de10)


## Desafio: API de Products
### 2. Listagem de Products na API

Da mesma forma que fizemos a listagem dos nossos Customers em nossa API, repita o mesmo processo e realize a listagem de Products. Não deixe de realizar o teste automatizado end-to-end.

[Commit do desafio 2](https://github.com/lucasfreitass10/FullCycle3CleanArchitecture/commit/eafe965e82e6517f08c6bac94668f1fe5d6e44ef)

## Desafio: Notification Pattern em Products
### 3. Evitando a geração excessiva de exceções

Aprendemos que o notification pattern nos auxilia como um container acumulador de erros para que possamos de uma forma mais simples retornarmos nossos erros todos de uma vez evitando assim a geração excessiva de exceções.

Nesse desafio você deverá utilizar o padrão notification em nossa entidade Products. Não deixe de realizar os testes automatizados.

Adicione um teste que acumule dois erros ao mesmo tempo. 

[Commit do desafio 3](https://github.com/lucasfreitass10/FullCycle3CleanArchitecture/commit/ac315a3aa81a10d68c5f9848748730d5360c3617)

## Desafio: Validação de Products
### 4. Validando entidade Product

Agora que aprendemos a criar o processo de validação, bem como minimizar o acoplamento em nosso domínio, você deverá realizar o processo de validação na entidade Product seguindo o mesmo processo.

OBS: Não deixe de verificar se todos os testes ainda estão passando.

[Commit do desafio 4](https://github.com/lucasfreitass10/FullCycle3CleanArchitecture/commit/5966248bb078c4584899bcd0fdb68320e899e781)

A linguagem de programação para estes desafios é **TypeScript**.