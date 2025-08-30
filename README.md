💻 **Sistema Web de Gestão de Cadastros**

Este projeto é um sistema web completo, criado com Java e Spring Boot no backend e HTML, CSS e Bootstrap no frontend. O objetivo é demonstrar a construção de uma aplicação robusta com persistência de dados em um banco PostgreSQL, gerenciando informações de cidades, funcionários e estados.

✅ **Funcionalidades Principais**

Gestão de Dados: Crie, edite, visualize e exclua informações de Cidades, Funcionários e Estados.
Persistência de Dados: Todos os dados são armazenados de forma segura em um banco de dados PostgreSQL.
Layout Moderno: A interface é construída com Bootstrap 5, garantindo um design responsivo e acessível em qualquer dispositivo.
Injeção de Dependências: O Spring Boot facilita a automação e a organização do código.

▶️ **Como Usar**

Pré-requisitos
Java Development Kit (JDK) 17+
Apache Maven
PostgreSQL (instalado e em execução)
Um editor de código como VS Code ou uma IDE como IntelliJ IDEA.
Configurar o Banco de Dados
Crie um banco de dados vazio no seu PostgreSQL (por exemplo, meu_banco_de_dados).
No arquivo de configuração do Spring Boot (src/main/resources/application.properties), atualize as credenciais do banco de dados com suas informações:
spring.datasource.url=jdbc:postgresql://localhost:5432/meu_banco_de_dados
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha

Executar o Projeto

Abra o projeto na sua IDE.

Execute a classe principal da aplicação (aquela com a anotação @SpringBootApplication).

O Spring Boot irá iniciar a aplicação em http://localhost:8080/administrativo

As tabelas do banco de dados serão criadas automaticamente pelo Spring Data JPA na primeira execução.

📦 **Estrutura do Projeto**

nome-do-seu-projeto/
├── src/main/java/com/seuprojeto/
│   ├── controller/      # Controladores que lidam com requisições
│   ├── model/           # Classes de entidade (Cidades, Funcionários, Estados)
│   ├── repository/      # Interfaces para acesso ao banco de dados
│   └── service/         # Lógica de negócio da aplicação
├── src/main/resources/
│   ├── static/          # Arquivos CSS, JS e imagens
│   ├── templates/       # Páginas HTML
│   └── application.properties # Configurações da aplicação
└── pom.xml                  # Gerenciador de dependências Maven

👤 **Autor**
Projeto desenvolvido para fins de aprendizado e demonstração de um sistema web completo, com back-end e front-end integrados, visando treinanr conceito de Programação orientada a objetos, Banco de dados Relacional, Spring Boot.

