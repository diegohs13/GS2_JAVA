# Easy Toy
## Descrição

Projeto de desenvolvimento com Spring para uma plataforma de conteudos de energia sustentavel.


## Integrantes

- MATHEUS MATOS - RM:99792
- KAREN VITORIA JESUS DA SILVA - RM:99468
- JULIANNY ARAUJO PEREIRA - RM:99554
- DIEGO HENRIQUE SANTOS DE OLIVEIRA - RM:550269
- JULIA DE FATIMA QUEIROZ - RM:551130

## Modelo de Dados

**TB_GS2_APP_USER**
- id (chave primária)
- username
- password<br>

**TB_GS2_CONTEUDO**
- id (chave primária)
- nome_conteudo
- corpo<br>

**TB_GS2_MODULO**
- id (chave primária)
- nome_modulo
- descricao<br>


## How to use
- Configure o arquivo `application.properties` com as configurações do seu banco de dados.
  ![img.png](img.png)

- Execute a classe `Gs2Application.java` para iniciar a aplicação.
  ![img_1.png](img_1.png)

- Acesse o endereço `http://localhost:8080/` para acessar a aplicação.
- Após isso, realize o login ou se registre para acessar os conteudos.

## Nome da Aplicação
Easy Eco