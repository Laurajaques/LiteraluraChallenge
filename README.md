Desafio LiterAlura Backend
Descrição

Este projeto é um backend em Java para gerenciamento de autores e livros, criado como parte do Desafio LiterAlura. Ele permite cadastrar autores, buscar livros em APIs externas e gerar relatórios personalizados.
O objetivo é praticar Java, Spring Boot, JPA/Hibernate e consumo de APIs externas, simulando funcionalidades de um sistema real de biblioteca.

Funcionalidades:

O sistema oferece as seguintes opções no menu:
Cadastrar autor manualmente – Adição de autores com informações básicas.

Listar autores – Visualizar todos os autores cadastrados.

Buscar livro na API – Consulta livros via API externa 

Listar livros – Visualização de todos os livros cadastrados

Buscar autores vivos em determinado ano – Filtra autores que estavam vivos em um ano específico.

Listar livros por idioma – Filtra livros pelo idioma em que foram publicados.

Top 10 livros mais baixados – Lista os livros mais populares conforme número de downloads.

Sair – Encerra a aplicação.


Tecnologias Utilizadas:

Java 17
Spring Boot
Spring Data JPA
Hibernate
Maven
H2 Database 
API externa para busca de livros (Gutendex)

Pré-requisitos:

JDK 17 ou superior
Maven
IDE de preferência: IntelliJ

Como Rodar o Projeto:

Clone o repositório
Entre na pasta do projeto
Configure as variáveis de ambiente - DB_USER:	Usuário do banco PostgreSQL	postgres | DB_PASSWORD:	Senha do usuário do banco
Execute o projeto com Maven
Interaja com o sistema através do menu no console.

Possíveis Melhorias:

Interface gráfica simples para interação com usuários.

Autor: Laura Jaques
