# Teste PHP

### Instruções

1. Bom base no wire Wire_Teste_PHP.png desenvolver um Micro Dashboard de Listagem de Palestras (detalhes abaixo)
2. Desenvolver um Micro REST para consumo do dashboard (detalhes abaixo)

##Micro Dashboard de Listagem de Palestras:

**Descrição:**
	O usuário deverá acessar o dashboard através de uma página de login e senha, caso o usuário não tenha cadastro, ele clicará para efetuar um novo, após o login ou novo cadastro o usuário será redirecionada para página de dashboard (Wire_Teste_PHP.png). Com uma opção de fazer logout. 

**Extra**: Usuário logado poderá fazer inserção de novos eventos.

**Pré-requisitos**:
* Toda as informações consumidas por essa stack deverão ser trazidas de um servidor REST (descritos mais abaixo).
* Implementação de design pattern indispensável para uma boa organização.
* Validações em JavaScript e apresentação de mensagem de erros ao usuário.
* Compliance com os navegadores mais comuns do mercado
* Modularização do Javascript é um PLUS.

##Micro REST (MVC)

**Descrição**:
O sistema deverá ter as rotas padrões e operações básicas de CRUD (Create, Retrieve, Update or Delete), das tabelas usuários e eventos. A tabela de usuários deverá conter nome do usuário, usuário/email, senha e token. O usuário deverá ser mantido logado via token. Pode ser JSON Oriented.

**Pré-requisitos**:
* Ser na linguagem: PHP
* Implementação dentro de algum framework PHP (Laravel 5.0>, preferivel)
* Implementação de opções extras de filtros de evento
* Implementação de validação do usuário e mensagem de erros.
* Conter algum design pattern.

**EXTRA**: Implementação do JWT.IO, (JSON WEB TOKEN). 

**PODE USAR**: Frameworks PHP (preferencialmente LARAVEL), Framework CSS, Framework JavaScript.

Ao terminar o teste, solicite um pull request.
