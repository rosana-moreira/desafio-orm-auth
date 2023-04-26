## Desafio para entregar


![uml](https://github.com/rosana-moreira/desafio-orm-autenticacao/blob/master/modelo-conceitual.png)

### Basicamente você deverá cumprir três etapas:

* Implementar o modelo conceitual proposto, com seed do banco de dados.
* Incluir a infraestrutura de exceções, validação e segurança ao projeto.
* Implementar o endpoint mostrado abaixo.

#### Requisitos do seed para os testes passarem:

Seu seed deve conter dois usuários:
* Usuário somente com perfil VISITOR:
   * email: bob@gmail.com
   * senha: 123456
* Usuário com perfil MEMBER:
   * email: ana@gmail.com
   * senha: 123456
   
Endpoint que deverá ser feito:

* Obter o perfil do usuário logado:   `GET /users/profile`
