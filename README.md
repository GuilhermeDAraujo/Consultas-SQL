# Projeto Banco de Dados de Filmes

Este projeto consiste na criação e manipulação de um banco de dados para um site de filmes. O banco de dados armazena informações sobre filmes, atores e gêneros, permitindo consultas complexas para análises detalhadas. A estrutura do banco de dados foi modelada para suportar relacionamentos muitos-para-muitos entre filmes e atores, assim como entre filmes e gêneros.

## Estrutura do Banco de Dados

O banco de dados é composto por cinco tabelas principais:

### Filmes

Tabela responsável por armazenar informações sobre os filmes. Esta tabela contém dados essenciais como título, ano de lançamento, e classificação.

### Atores

Tabela responsável por armazenar informações sobre os atores. Esta tabela contém dados pessoais dos atores como nome, data de nascimento, e nacionalidade.

### Generos

Tabela responsável por armazenar os gêneros dos filmes. Cada registro nesta tabela representa um gênero cinematográfico, como ação, comédia, drama, entre outros.

### ElencoFilme

Tabela de relacionamento muitos-para-muitos entre filmes e atores. Esta tabela permite associar múltiplos atores a um filme e múltiplos filmes a um ator, possibilitando consultas detalhadas sobre o elenco de cada filme.

### FilmesGenero

Tabela de relacionamento muitos-para-muitos entre filmes e gêneros. Esta tabela permite associar múltiplos gêneros a um filme e múltiplos filmes a um gênero, facilitando consultas sobre a diversidade de gêneros em cada filme.

## Consultas

Foram realizadas 12 consultas ao banco de dados para extrair diferentes tipos de informações. Essas consultas abrangem uma variedade de análises, incluindo:

1. Listagem de todos os filmes.
2. Listagem de todos os atores.
3. Filmes de um determinado gênero.
4. Atores que participaram de um determinado filme.
5. Filmes lançados em um determinado ano.
6. Gêneros de um determinado filme.
7. Filmes em que um determinado ator atuou.
8. Número de filmes por gênero.
9. Número de filmes por ator.
10. Número de atores por filme.
11. Filmes de um determinado ator em um determinado gênero.
12. Atores que mais atuaram em filmes de um determinado gênero.

## Tecnologias Utilizadas

- **Banco de Dados**: Microsoft SQL Server
- **Linguagem SQL**: Utilizada para escrever as consultas e interagir com o banco de dados.
- **.NET**: Utilizado para a interface e interação com o banco de dados, bem como para a execução das consultas.

## Como Utilizar

Para utilizar este projeto, siga as instruções abaixo:

1. Clone este repositório para o seu ambiente local.
2. Configure o banco de dados conforme o diagrama fornecido.
3. Importe os dados necessários para as tabelas `Filmes`, `Atores`, `Generos`, `ElencoFilme` e `FilmesGenero`.
4. Execute as consultas SQL fornecidas no diretório `queries` para realizar as análises desejadas.

Este projeto foi desenvolvido como parte da trilha .NET da DIO, aplicando os conhecimentos adquiridos no módulo de banco de dados para a construção de consultas complexas e gerenciamento de relacionamentos muitos-para-muitos.
