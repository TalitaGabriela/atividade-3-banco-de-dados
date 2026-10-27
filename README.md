# Atividade 3 - Banco de Dados (Gerenciamento de Projetos)

Atividade da disciplina de Banco de Dados deste semestre.

## Descrição

Script SQL com a modelagem de um banco de dados para gerenciamento de projetos acadêmicos, incluindo professores, recursos (equipamentos e materiais), projetos, atividades e alunos voluntários.

Contém:

- Criação do banco `gerenciamento_projetos` e das tabelas principais (`professor`, `recurso`, `equipamento`, `material`, `projeto`, `atividade`, `aluno_voluntario`, `atividade_aluno`), com chaves primárias, estrangeiras e restrições (`CHECK`, `UNIQUE`, índices).
- Atividades de fixação (22/08/2026) com comandos `ALTER TABLE` para adicionar, renomear, alterar tipo e remover colunas, além da criação de um índice.

## Como executar

Executar o arquivo `curso.sql` em um servidor MySQL/MariaDB, por exemplo:

```bash
mysql -u usuario -p < curso.sql
```
