# Tema 2 - Sistema de Gestão Acadêmica
---
## 1. Entendimento do Problema:

Neste projeto será desenvolvido um sistema com a intenção de organizar as informações, notas, médias delas e a situação do aluno em questão.

O sistema deverá centralizar informações sobre alunos, cursos, disciplinas, turmas, matrículas e desempenho acadêmico, facilitando o cadastro, consulta e acompanhamento dessas informações.

O objetivo é automatizar tarefas básicas de gerenciamento acadêmico, permitindo o armazenamento organizado dos dados e a realização de consultas e cálculos relacionados ao desempenho dos alunos.

## 2. Entidade Central e Atributos Mínimos:

A arquitetura de dados orientada a objetos simplificada do sistema baseia-se na entidade central **Aluno**, contendo os seguintes atributos fundamentais:

- **ra (int)**: Chave primária do aluno no sistema, ou seja, seu identificador numérico.
- **nome (String)**: Nome e identificação do aluno.
- **idade (int)**: Idade aproximada em anos.
- **email (String)**: Email de contato do aluno.
- **curso (String)**: Curso em que o aluno está inscrito.
- **semestre (int)**: Período do curso em que o aluno se encontra.
- **status (String)**:Situação acadêmica do aluno (ativo, trancado ou formado).
- **notas por semestre (int)**: Exibição das notas do aluno.

## 3. Escopo e Diretrizes de Implementação:

**Orientações Gerais:** O sistema será desenvolvido em linguagem Java, seguindo estritamente as regras de modularização, uso correto de estruturas de dados e versionamento contínuo via GitHub, conforme especificado no regulamento da disciplina.

O escopo inicial compreenderá o cadastro e gerenciamento de alunos, disciplinas e informações relacionadas ao desempenho acadêmico.

A implementação será realizada de maneira incremental, acrescentando funcionalidades conforme os conteúdos trabalhados em cada aula e previstos em cada etapa, assim como descrito pelo professor.

## 4. Requisitos Funcionais e Cronograma de Entregas:

### Assim como descrito acima, o sistema será construído de forma modular e incremental, dividindo-se nas cinco etapas previstas no cronograma oficial da disciplina.

| Etapa | Conceito Principal | Funcionalidade Descrita |
|---|---|---|
| **E1** | Vetores (Arrays) | Cadastro e listagem de alunos utilizando vetores paralelos, busca linear por RA e cálculo de estatísticas básicas, como idade média e maior/menor idade. |
| **E2** | Matrizes | Controle bidimensional das notas dos alunos em diferentes disciplinas, permitindo calcular médias por aluno e por disciplina, além de identificar maiores e menores notas. |
| **E3** | Strings e Validação | Validação do formato do RA, nome e e-mail dos alunos e geração de relatório formatado com informações acadêmicas. |
| **E4** | Métodos e Modularização | Reorganização do sistema em métodos reutilizáveis para cadastro, busca, cálculo de médias, validação e exibição de informações, reduzindo a concentração de funcionalidades no método principal. |
| **E5** | Manipulação de Arquivos | Persistência dos dados dos alunos e das informações acadêmicas em arquivos de texto, permitindo recuperar os dados cadastrados entre diferentes execuções do programa. |

## 5. Funcionalidades do sistema:

1.Cadastro dos alunos<br>
2.Registrar notas<br>
3.Busca de alunos por RA<br>
4.Cálculo da média dos alunos<br>
5.Determinar situação acadêmica<br>
6.Identificação e exibição da maior e menor nota<br>
7.Cálculo geral da média da turma<br>

## 6. Considerações Finais:

Esta proposta técnica consolida o planejamento inicial do desenvolvimento do software. O escopo apresentado atende integralmente aos critérios da rubrica de avaliação, assegurando a robustez pedagógica e técnica exigida para a aprovação na disciplina de Linguagem de Programação I.