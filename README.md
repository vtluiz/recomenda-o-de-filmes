# Sistema de Recomendação de Filmes

Este projeto implementa um sistema básico de recomendação de filmes usando SQL.

## Estrutura do Banco de Dados

O banco de dados contém as seguintes tabelas:

1. **Generos**: Armazena os gêneros dos filmes.
2. **Filmes**: Informações sobre os filmes, como título, ano de lançamento e gênero.
3. **Usuarios**: Informações sobre os usuários do sistema.
4. **Avaliacoes**: Avaliações dadas pelos usuários aos filmes.

## Comandos Principais

### Criação das Tabelas

As tabelas são criadas utilizando o script SQL em `src/database.sql`.

### Inserção de Dados

Exemplo de inserção de dados:

```sql
INSERT INTO Generos (descricao) VALUES ('ação'), ('comédia');
INSERT INTO Usuarios (nome_usuario) VALUES ('Usuario 1'), ('Usuario 2');
INSERT INTO Filmes (titulo, ano_lancamento, id_genero) VALUES ('Bad Boys', 1995, 1);
