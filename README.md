# Sistema de Cadastro de Alunos (em C)

Este é um sistema simples feito em C para gerenciar cadastros de alunos, suas notas e situação acadêmica. O programa permite cadastrar, listar, adicionar notas e excluir alunos, além de calcular a situação com base nas notas inseridas.

# Funcionalidades

- Cadastro de alunos com nome, RGM e e-mail
- Registro de notas A1, A2 e Avaliação Final (AF)
- Cálculo automático da situação do aluno:
  - Aprovado
  - Em avaliação final
  - Aprovado após AF
  - Reprovado
- Listagem de todos os alunos cadastrados
- Exclusão de alunos com base no RGM

# Como usar

# Requisitos

- Compilador C (ex: `gcc`)
- Terminal ou IDE que permita entrada via `scanf` (como o Code::Blocks, Dev-C++, etc)

# Compilação

No terminal, utilize:

```bash
gcc -o cadastro_alunos main.c
