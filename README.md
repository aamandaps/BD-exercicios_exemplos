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
