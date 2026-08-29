## Banco de Dados I - Exercícios
### Exercício 01
#### 
Uma livraria mantém o cadastro de livros disponíveis para a venda. Para cada livro são
armazenados código, nome, língua e ano em que foi escrito. Para os autores é mantido
igualmente um cadastro que inclui nome, data de nascimento, pais de nascimento e uma
breve nota biográfica.
Cada livro pode ter vários autores e para um mesmo autor podem existir vários livros
cadastrados. Um autor pode estar incluído no cadastro ainda quando não exista um livro seu
para venda.
As editoras são incluídas no cadastro a partir do seu nome, endereço, telefone. Uma editora
pode estar cadastrada mesmo quando não existam livros editados por ela em venda.
Para um mesmo livro podem existir várias edições realizadas por editoras diferentes ou em
anos difrentes . Cada edição tem um código (ISBN) , preço, ano, número de páginas e
quantidade em estoque.
Considere que um livro pode ser cadastrado se existe pelo menos uma edição do mesmo
para venda.

---

### Exercício 02
####
Uma locadora mantém um cadastro de todos seus usuários com as informações básicas:
RG, nome, endereço, CNH e idade. Todo usuário cadastrado pelo menos realizou uma
locação na empresa.
Cada carro da frota é registrado com vários atributos para sua descrição: número de chassi,
placa, marca, modelo, ano e cor. Quando um usuário aluga um carro são registradas data e
hora de locação.
Os carros da frota são organizados por categorias. Uma categoria é descrita por código, um
nome de categoria (Ex: Primeira classe) , preço da diária da categoria e uma descrição das
características dessa categoria. Todo carro pertence a uma categoria que define suas
características e o preço da diária.

---

### Exercício 03
####
Uma academia de ginástica deseja manter um controle do seu funcionamento. Os alunos
são organizados em turmas associadas a um tipo específico de atividade. As informações
sobre uma turma são número de alunos, horário da aula, duração da aula, data inicial, data
final e tipo de atividade. Cada turma é orientada por um único instrutor para o qual são
cadastrados RG, nome, data de nascimento, titulação e todos os telefones possíveis para sua
localização. Um instrutor pode orientar várias turmas que podem ser de diferentes
atividades. Os dados cadastrados dos alunos são: código de matricula , data de matrícula,
nome, endereço, telefone, data de nascimento, altura e peso. Um aluno pode estar
matriculado em várias turmas se deseja realizar atividades diferentes e para cada matrícula
é mantido um registro das ausências do aluno. Para cada turma existe um aluno monitor que
auxilia o instrutor da turma, sendo que um aluno pode ser monitor no máximo em uma
turma.

---

### Exercício 04
####
Um hotel mantém o cadastro de seus clientes com RG, nome, fone e sexo. Os clientes
podem reservar quartos do hotel para uma determinada data e por uma certa quantidade de
dias. Os quartos são cadastrados por número, andar, tipo, descrição e preço. Para os quartos
já ocupados pelos clientes, é mantida a data/hora de entrada e de saída do quarto, isto é,
existe um registro diferenciado de quartos reservados e quartos ocupados. Para um cliente
ficar cadastrado é suficiente que tenha feito uma reserva alguma vez embora não tenha
ocupado efetivamente o quarto.
Os clientes que ocupam um quarto do hotel podem solicitar determinador serviços
que são registrados associados ao quarto ocupado para posterior cobrança. Destes serviços
são armazenados um código, tipo, descrição e valor.
Para cada carro da frota é mantido um histórico dos reparos realizados, indicando dia,
valor, descrição do serviço e oficina que o realizou.

---

## Exercícios Banco de Dados I - Segunda Parte
### Exercício 01
####
Para se desenvolver um aplicativo de música se pensou nas seguintes regras:
É necessário armazenar as músicas, com um identificador (ID), seu nome e tempo de duração.
Todas as músicas pertencem a um disco que tem um código, um nome e um ano de
lançamento. As músicas de cada disco são associadas a apenas um cantor ou banda (Caso
exista parceria, é importante se armazenar uma descrição da música que conste a parceria ou
qualquer outro dado relevante). Os cantores/banda, que podem ter diversos discos, com
diversas músicas no sistema, são cadastrados por um código identificador, seu nome e uma
URL com a foto.
O aplicativo deve cadastrar os usuários pelo seu e-mail (único), seu nome, seu telefone (com o
qual se recupera a conta), login e senha. O app tem diversos planos com um identificador, um
nome e um valor. Cada usuário tem apenas um plano.
Um usuário pode criar playlists com diversas músicas e cada playlist tem um ID e um nome.

---

### Exercício 02
Considere as seguintes informações sobre um banco de dados de um centro de pesquisa de
uma universidade:

• Os professores têm um CPF, um nome, uma idade, uma posição e uma especialidade de
pesquisa;

• Os projetos têm um número de projeto, um nome de financiador (por exemplo, CNPQ), uma
data inicial, uma data final e um orçamento;

• Os estudantes de pós-graduação têm um CPF, um nome, uma idade e um programa de pós-
graduação (por exemplo, mestrado ou doutorado);

• Cada projeto é gerenciado por um professor (conhecido como pesquisador principal do
projeto);

• Cada projeto é conduzido por um ou mais professores (conhecidos como copesquisadores);

• Os professores podem gerenciar e/ou trabalhar em múltiplos projetos;

• Cada projeto é conduzido por um ou mais estudantes de pós-graduação (conhecidos como
os assistentes de pesquisa do projeto). Neste caso, cada estudante deve ter um professor para
supervisionar seu trabalho no projeto. Os alunos de pós-graduação podem trabalhar em
múltiplos projetos, e, neste caso, eles terão um supervisor (potencialmente diferente) para
cada projeto;

• Os departamentos têm um número de departamento, um nome e um escritório principal;

• Os departamentos têm um professor (conhecido como chefe do departamento) que o
administra;

• Os professores trabalham em um ou mais departamentos e, para cada departamento em que
trabalham, uma porcentagem de tempo está associada a seu trabalho;

• Os alunos de pós-graduação têm um departamento principal no qual estão conduzindo seu
programa de pós-graduação;

• Cada estudante tem um outro estudante mais experiente (conhecido como conselheiro do
aluno) que o aconselha nos cursos a que deve assistir.
