# CSistema de Controle de Estoque
Integrantes: Hugo Gustavos dos Santos pinto, Kaio Ribeiro Rodrigues.
/*aqui deve explicar como compilar*/

# Cadastro de produtos
/*O código fonte das seguintes funções está em pessoas.c, com seus headers em pessoas.h
* 1 - Cadastrar: A função cadastrar insere os dados de uma pessoa, Nome, Sobrenome, Brasileiro? (0 - Brasileiro, 1 - Estrangeiro), Caso seja Brasileiro: Número do CPF e Número do RG, Caso seja estrangeiro: Número do Passaporte e Nome do País de Origem,
Dia, mês e ano de nascimento, Portador de Necessidades Especiais (PNE)? (0 - Não, 1 - Sim), Caso seja PNE, deve possuir um código  de 10 caracteres do Laudo médico, CEP, Endereço, Aluno? (0 - Aluno, 1 - Professor).
Lembrar que os dados que serão inseridos devem seguir o padrão de entrada e o padrão dos dados, como o tamanho do cpf(11 números), tamanho do rg(9 números), passaporte de acordo com o modelo padrão do país, data padrão DD/MM/AAAA, tamanho do cep(8 números),  pis(11números), e a matrícula será incrementada automáticamente em relação a quantidade de alunos inseridos no cadastro de pessoas.
A entrada deve ser feita da seguinte forma, cada dado do usuário deve ser seguido de um ";" em uma linha só de entrada.
Exemplos:

Caso seja Brasileiro, não PNE e é um aluno: 

nome;sobrenome;0;CPF;RG;DD/MM/AAAA;0;CEP;ENDEREÇO;0

Caso seja Brasileiro, PNE e é um aluno:

nome;sobrenome;0;CPF;RG;DD/MM/AAAA;1;LAUDO;CEP;ENDEREÇO;0

Caso seja Brasileiro, não PNE e é um professor:

nome;sobrenome;0;CPF;RG;DD/MM/AAAA;0;CEP;ENDEREÇO;1;PIS

Caso seja Brasileiro, PNE e é um professor:

nome;sobrenome;0;CPF;RG;DD/MM/AAAA;1;LAUDO;CEP;ENDEREÇO;1;PIS

* 2- Remover: A função remover, remove uma pessoa, aluno ou professor, caso ela não esteja inserido em uma disciplina, caso ele esteja em alguma disciplina, ele não será apagado. Logo será necessário apagar a pessoa na disciplina antes de apagar do registro de pessoas, caso ela não esteja em nenhuma disciplina, ela seŕá apagada do registro de pessoas.
Seguir as opções que aparecem para o usuário.

* 3- Exibir todos os dados: A função exibirdados exibe todas as pessoas já cadastradas no registro de pessoas, alunos ou professores.

* 4- Alterar dados de uma pessoa: A função alterarDados altera dados específicos de uma pessoa.
Para alterar os dados de uma pessoa, o usuário deverá escolher se a pessoa é um professor ou um aluno, posteriormente deverá inserir o pis, caso seja um professor ou a matrícula, caso seja um aluno(para localizar a pessoa).
Então poderá ser escolhido qual dado da pessoa será alterado entre as seguinte opções:
1. Portador de Necessidades especiais?;
2. Código do laudo médico;
3. CEP;
4. Endereço;
A função só admite mudança caso o novo dado seja diferente do anterior, caso seja igual será imprimida uma mensagem de erro.

* 5- Exibir pessoa específica: A função exibe_pessoax  serve para exibir os dados de uma pessoa específica do programa, perguntando se ela um professor ou aluno, as informações que devem ser exibidas são, caso seja um professor, deve-se receber um número de PIS, e caso seja um aluno deve-se receber um número de matrícula. Por fim, deve-se exibir todos os dados de uma determinada pessoa. Caso esta pessoa não exista, exibe-se uma mensagem de erro. Exibindo-se assim todas as informações da pessoa, ignorando as informações que não existem, logo a função só exibe as iformações que aquela pes

* 6- Função de ajuda: A função help serve apenas para exibir o menu de opções.*/]

# atualizar informações de um produto


#vender produto  
#consultar informacoes de um produto
#consultar quantidade de todos produtos;   

  
