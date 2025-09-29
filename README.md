# Biblioteca de Jogos - Spring Boot

Biblioteca de Jogos é uma aplicação web full stack desenvolvida com Spring Boo permitindo cadastrar, listar, editar e remover jogos. Possui tema Dark/Light e rodapé fixo com informações do desenvolvedor.

---

## 🛠 Tecnologias Utilizadas

- **Java 21**
- **Spring Boot**
- **Thymeleaf**
- **Bootstrap 5**
- **H2 Database** (desenvolvimento)
- **PostgreSQL** (produção)
- **Maven** como gerenciador de dependências

---

Executando Localmente

1. Clonar o repositório

git clone https://github.com/CarlosEZaul/bibliotecajogos.git
cd bibliotecajogos

2. Configurar o banco de dados
spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username=sa
spring.datasource.password=
spring.h2.console.enabled=true
spring.jpa.hibernate.ddl-auto=update

Deploy no Render
1. Criar um Web Service

Acesse Render
 e faça login.

Clique em New e depois Web Service.

Conecte o repositório GitHub do projeto.
