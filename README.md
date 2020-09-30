# Sistema de Controle de Estoque
Integrantes: Hugo Gustavos dos Santos pinto, Kaio Ribeiro Rodrigues.

foram utilizadas somente bibliotecas padrões neste projeto

o codigo foi criado e compilado na IDE codeblocks versao 20.03

optamos por ela pois, alguns comandos não são aceitos no replit.

quando se cria um projeto no codeblocks, ele ja gera todos os arquivos necessarios para a execução do codigo, é necessario que se execute todos
os arquivos pertencentes ao projeto simultaneamente.


o sistema operacional utilizado foi WINDOWS 10 

# Cadastro de produtos

* 1 - Cadastrar novo produto: Ao selecionar a opção de n° 1 o programa deve cadastrar um novo produto
recebendo do usuário as seguintes informações (Além das seguintes mensagens
para o usuário):

	*Nome do produto
	
	*País de origem
	
	*Quantidade de itens
Após isso deve ser gerado um novo código de acordo com a ordem de registro do produto.

* 2- Atualizar informações de um produto: Ao selecionar a opção de n° 2 o programa deve receber como entrada o
código do produto. Caso não encontre o produto deve-se emitir a mensagem
“Código inválido!” e voltar ao menu principal. Caso o encontre deve-se exibir o
seguinte menu:
	*Alterar nome: O produto recebe um novo nome para o produto;
	*Alterar país de origem: O produto recebe um novo país de origem;
	*Adicionar mais itens: O produto recebe uma quantidade de itens a ser
adicionado ao estoque atual.


* 3- Vender produto: Ao selecionar a opção de n° 3 deve-se receber como entrada o código do
produto. Caso não encontre o produto deve-se emitir a mensagem “Código
inválido!” e voltar ao menu principal. Caso o encontre deve-se receber a
quantidade de itens a serem vendidas.
	-A quantidade de itens a ser vendido deve ser maior ou igual a zero e
	não deve ser maior que o estoque disponível. Caso seja negativo,
	deve-se emitir a mensagem: “Valor inválido, digite novamente” e
	receber uma nova quantidade. Caso seja maior, deve-se emitir a
	mensagem “Não existem itens suficientes para este produto” e
	receber uma nova quantidade.
Após a venda do produto deve-se voltar ao menu principal.


* 4- Consultar informções de um produto: Ao selecionar a opção de n° 4 deve-se receber como entrada o código do
produto. Caso não encontre o produto deve-se emitir a mensagem “Código
inválido!” e voltar ao menu principal. Caso o encontre deve-se exibir todas as informações contidas deste produto.

* 5- Consultar quantidade de todos os produtos: Ao selecionar a opção de n° 5 deve-se exibir todos os produtos (Código de
Barras e quantidade de itens), um em cada linha.
