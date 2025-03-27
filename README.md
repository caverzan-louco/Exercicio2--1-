//Conectando ao banco de Dados:

Seguimos como base a atividade anterior, e usamos os dois seguintes arquivos para conectar ao banco de dados:


O arquivo database.js foi usado para conectar o vscode com o mysql. Enquanto o arquivo Cadastrar.js foi usado para criar a tabela no mysql e definiu os tipos de dados que serão inseridos.







//Index.js:

Também usamos como base o arquivo da atividade anterior, e fizemos as devidas modificações:

-Primeiro, alteramos os nomes antigos dos arquivos para os novos, que serão utilizados. Sendo assim, o “pergunta.ejs” passou a ser “produto.ejs”, e o “perguntar.ejs” passou a ser “cadastrar.ejs”. Devido a mudança dos nomes dos arquivos, também tivemos que alterar os nomes no código.

-Atualizamos a área “salvar cadastro” para permitir salvar os novos tipos de dados, incluindo imagens.



-Adicionamos a const “multer”, que é uma biblioteca do node.js para gerenciar uploads de arquivos em um servidor, facilitando o recebimento e armazenamento de arquivos enviados pelo usuário.


//Interface:

A interface foi feita nos arquivos “index.ejs”, “produto.ejs” e “cadastrar.ejs”.

Na index.ejs, está a tela inicial, onde adicionamos um botão que te leva para a tela de cadastro de produto.


Também há um card que pega os dados dos produtos cadastrados do banco de dados e os exibe, além de um botão que te leva a uma tela que mostra mais detalhes do produto.


Em produto.ejs, é exibido os dados dos produtos cadastrados do banco de dados, similar ao que acontece nos cards do index.ejs, porém mais dados são exibidos, como a imagem do produto.


Em cadastrar.ejs, há input e textarea para digitar os dados do produto que está sendo cadastrado.


E também um botão para enviar os dados e cadastrar o produto



//Dificuldades:

 Não tivemos dificuldades em fazer a conexão com o banco de dados devido às demais aulas e atividades sobre o assunto, que nos deu conhecimento o bastante para realizar tal feito sem grandes dificuldades.

  Entretanto, tivemos dificuldade na área do css, pois as imagens não se ajustavam no tamanho que desejávamos, mas principalmente, não conseguíamos decorar as páginas como queríamos, devido ao bootstrap, que estava sobrepondo as alterações feitas pelo style.css. Porém eventualmente conseguimos resolver o problema, e não tivemos mais nenhum outro grande desafio. Tudo correu muito bem.


