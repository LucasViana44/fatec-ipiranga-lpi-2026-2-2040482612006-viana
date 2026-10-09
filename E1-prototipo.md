### Tópico 1: Mapa do Menu:

**Opção 1**: Cadastrar e registrar Alunos e suas respectivas Notas bimestrais. <br>
**Opção 2**: Exibir Relatório das notas. <br>
**Opção 3**: Exibir tabela de aprovados/reprovados. <br>
**Opção 4**: Correção de notas. <br>
**Opção 0**: Saída. <br>

### Tópico 2: Prototipagem do console

**Simulação de Exibição do Console:** <br>
PS: Nesta parte o programa utilizará um laço do tipo for, percorrendo um array com o número de alunos. <br>
Informe o RA do Aluno: 1234567 <br>
Informe o Nome do Aluno: Fulano <br>
Informe a primeira Nota Bimestral do Aluno: 6.7 <br>
Informe a segunda Nota Bimestral do Aluno: 6.7 <br>
Informe a terceira Nota Bimestral do Aluno: 6.7 <br>
Informe a quarta Nota Bimestral do Aluno: 6.7 <br>
----------------------------------- <br>
**Definição da quantidade de alunos** <br>
Insira a Quantidade de Alunos na Turma: 4 <br>
**Relatório das Notas** <br>
Aluno: Fulano <br>
Nota 1: 6.7 <br>
Nota 2: 6.7 <br>
Nota 3: 6.7 <br>
Nota 4: 6.7 <br>
Média do Aluno: 6.7 <br>
---------------------------------- <br>
**Situação dos Alunos** <br>
Fulano: Aprovado <br>
Ciclano: Reprovado <br>
Beltrano: Reprovado <br>
Paulo: Reprovado <br>
... <br>
---------------------------------- <br>

### Tópico 3: Regras de Validação de Entrada:


| Tipo de validação | Regra | Exemplo |
|-------------------|-------|---------|
| Campos obrigatórios | Não permitir campos essenciais vazios. | Nome do aluno e RA são obrigatórios. |
| Tipo de dado | Aceitar apenas o tipo de dado esperado. | Nota deve ser numérica. |
| Formato | Verificar se os dados seguem um padrão definido. | Nota deve ser informada atendendo ao padrão exigido. |
| Tamanho máximo e mínimo | Limitar a quantidade de caracteres ou dígitos. | Nome deve ter entre 3 e 100 caracteres. |
| Faixa de valores | Restringir valores a um intervalo permitido. | Nota entre 0.0 e 10. |
| Unicidade | Impedir registros duplicados quando não forem permitidos. | RA não pode pertencer a dois alunos. |
| Integridade referencial | Garantir que registros relacionados existam. | Um RA deve estar vinculado a um aluno e a uma disciplina cadastrados. |
| Regras de negócio | Validar condições específicas do sistema. | Um aluno só pode se matricular em uma disciplina se cumprir os pré-requisitos

### Tópico 4: Assinatura dos Métodos: 

- Aluno[] lerAlunos(): solicita a quantidade de alunos da turma, lê os dados e as notas de cada aluno em um laço `for` e retorna o array preenchido.

- double calcularMedia(Aluno aluno): calcula e retorna a média das notas de um aluno.

- String verificarSituacao(double media): verifica se o aluno está aprovado ou reprovado com base na média obtida.

- void exibirResultado(Aluno aluno, double media, String situacao): exibe o nome, a média e a situação acadêmica de um aluno.

- void exibirResultados(Aluno[] alunos): percorre o array de alunos, calcula as médias, verifica as situações e exibe os resultados individuais.





