# Star Schema Professores

Este projeto implementa um esquema em estrela (star schema) para professores, utilizando o banco de dados PostgreSQL. O foco é centralizar informações sobre professores, cursos ministrados, departamentos, disciplinas e datas.

## Estrutura do Banco de Dados

### Tabela Fato

- **FatoProfessor**: Centraliza informações sobre professores, cursos ministrados, departamentos, disciplinas e datas.

### Tabelas Dimensão

- **DimensaoProfessor**: Detalhes sobre os professores.
- **DimensaoDepartamento**: Detalhes sobre os departamentos.
- **DimensaoCurso**: Detalhes sobre os cursos.
- **DimensaoDisciplina**: Detalhes sobre as disciplinas.
- **DimensaoData**: Detalhes sobre as datas, incluindo ano, mês, dia, trimestre e semestre.

## Tecnologias Utilizadas

- **PostgreSQL**: Utilizado para a criação e manipulação das tabelas e dados.
- ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000?style=for-the-badge&logo=postgresql)
