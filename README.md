### atividade-semana12
<br> 

![Imagem ilustrativa banco de dados](./imagens_banco_dados/b-dados.png)


# Banco de dados

<br>

<p>Bancos de dados ou bases de dados são conjuntos de arquivos relacionados entre si com registros sobre pessoas, lugares ou coisas.</p>
<p>São coleções organizadas de dados que se relacionam de forma a criar informações capazes dar mais eficiência durante uma pesquisa, análise ou estudo cientifico.</p>
<p>As bases de dados são de vital importância para empresas e são utilizadas para armazenar diversos tipos de informações, desde dados sobre uma conta de e-mail até dados importantes da Receita Federal. A principal aplicação de Banco de Dados é o controle de operações empresariais.</p>
<p>De forma simplificada, podemos dizer que um banco de dados é uma coleção de dados que devem ser armazenados ou persistidos. Em um banco de dados, as informações são gravadas em memórias de longo prazo e mesmo que o computador seja desligado, os dados não serão perdidos. Dizemos que esses dados persistem.</p>
<p>Existe uma distinção entre banco de dados e sistema gerenciador do banco de dados (SGBD). 
<p>Um Sistema de Gerenciamento de Banco de Dados (SGBD) é o conjunto de softwares responsáveis pelo gerenciamento de um banco de dados. Seu principal objetivo é retirar da aplicação cliente a responsabilidade de gerenciar o acesso, a persistência, a manipulação e a organização dos dados.</p>

<br>

# Entidades e Atributos

<br>

<p>Uma entidade é uma representação de um conjunto de informações sobre determinado conceito. Toda entidade possui atributos, que são as informações que referenciam a entidade. Uma entidade é representada por um conjunto de atributos.</p>
<p>Para saber se determinado conceito pode ser uma entidade ou não, basta se  perguntar: " Desejo armazenar quais informações sobre este conceito? ". Se houverem informações a serem armazenadas, você tem uma entidade. </p>
<p>Vamos apresentar dois exemplos. Primeiro exemplo, desejamos armazenar os seguintes dados do livro: Título, Autor, Editora, Ano, Edição e Volume. Logo , temos a entidade Livro.</p>
<p>Desejamos armazenar os seguintes dados sobre a pessoa: Nome, Data de nascimento, Filiação, Sexo, RG, CPF e Grau de escolaridade. Então, temos a entidade pessoa. </p>

<br>

# Sistemas de Gerenciamento de Banco de Dados

<br>
<p>Os SGBDs são utilizados para gerir as estruturas de armazenamento dos dados, permitindo a realização de manipulações, bem como o controle das permissões de utilização dos bancos de dados.</p>
<p>Todas as organizações possuem quantidades cada vez maiores de dados e informações a serem armazenadas. Porém, a manipulação dessas informações tornou-se impossível de ser realizada manualmente, pois sua utilização, além de demorada devido a catalogação dos dados, é passível de erros, principalmente ocasionados pelo desgaste do operador em conseguir resgatar informações requisitadas.</p>
<p>Qualquer empresa que pretenda garantir um controle efetivo sobre todo o seu negócio tem que recorrer a sistemas de gestão de bases de dados. Nesse sentido, torna-se mais fácil encontrar a informação em uma base de dados baseada em uma tecnologia mais confiável - o computador. </p>

## Exemplos de SGBDs:

- PostgreSQL; <br>
- MySQL;<br>
- Oracle;<br>
- MongoDB;<br>
- MariaDB;<br>
- Microsoft SQL Server, dentre outros. <br>
<br>

![Imagem MongoDB](./imagens_banco_dados/mongodb.png)

<br>
<p>O MongoDB é um software não relacional de banco de dados orientado a documentos livre, de código aberto e multiplataforma, escrito na linguagem C++.</p>
<p>Como dito anteriormente, é classificado como um programa de banco de dados NoSQL (não relacional) e usa documentos semelhantes a JSON com esquemas. </p>
<p>Um banco de daos NoSQL permite adicionar novos campos; expandindo desta forma o banco de dados livremente e com campos diferentes.</p>
<p>Um registro no MongoDB é um documento, que é uma estrutura de dados composta de pares de campo e valor.</p>
<p>Os documentos do MongoDB são semelhantes aos objetos JSON. O MongoDB armazena documentos em coleções.</p>
<p>O MongoDB oferece uma versão Community totamente gratuita e disponível para Windows, Linux e MacOS.</p>

<br>

## Instalação e Tutorial

<br>

<p>A instalação do MongoDB Community versão gratuita e atualizada para Windows pode ser feita na url abaixo:

[Download do MongoDB Community]( https://www.mongodb.com/try/download/community )
</p>
<p>Assista a um tutorial explicativo para configurar adequadamente seu MongoDB: </p>

[Instalando e configurando o MongoDB no Windows](https://www.youtube.com/watch?v=skK5xj-CK-Q)

<br>

## Comandos utilizados no MongoDB no Prompt de Comando (cmd) :

- Digite : mongod - no terminal/prompt de comando (cmd) para subir o servidor .

<br>

![Terminal executando o comando mongod](./imagens_banco_dados/cmd_mongod.png)

<br>

- Digite : mongo  - em um outro prompt de comando (cmd) e o utilize para inserção dos comandos para criação do banco de dados e manipulação dos dados.

<br>

![Terminal executando o comando mongo](./imagens_banco_dados/cmd_mongo.png)

<br>  

<p>Estes dois terminais deverão estar abertos simultâneamente. As imagens mostram o que deverá estar sendo exibido nos prompts de comandos para validar a instalação exitosa.</p>

## Comandos do MongoDB :
<br>
<p>1. Para criação de um Banco de dados:</p> 

- <p>use [ nomeDoBancoASerCriado ]</p>

<p>2. Para mostrar seus bancos de dados</p>

- <p>show databases</p>

<p>3. Para criar uma collection :</p>

- <p>db.createCollection( "nomeDaCollection" )</p>

<p>O comando apresentado agora não deverá ser executado a menos que deseje, de fato, apagar o seu banco de dados. Está sendo apresentado apenas com fins de aprendizagem. TENHA CUIDADO COM ESTE COMANDO!</p> 

<p>4. Para DELETAR todos os bancos :</p>

- <p>db.dropDatabase( ) </p>

<p>5. Para mostrar todas as collections :</p>

- <p>show collections</p>

<p>6. Exibe registros :</p>

- <p>db.nomeDaCollection database</p>

<p>7. Comando que mostra o banco que está sendo usado no momento :</p>

- <p>db.current </p>

<p>8. Saia do Shell</p>

- <p>quit ( )  ou  Ctrl + C</p>

<p>9. Seleciona todos os documentos em uma coleção e os retorna.</p>

- <p>db.nomeDaCollection.find ( )</p>

<p>10. Comando que retorna um documento que satisfaz os critérios de consulta especificados na coleção. Se vários documentos satisfizerem a consulta, este método retornará o primeiro documento de acordo com a ordem natural que reflete a ordem dos documentos no disco, isto, retorna um único registro. </p>

- <p>db.nomeDaCollection.findOne ( )</p>

<p>11. Insere um documento ou documentos em uma coleção.</p>
    
- <p>db.nomeDaCollection.insert( )</p>

<p>O insert( ) método possui a seguinte sintaxe : db.nomeDaCollection.insert (
    {
     " nome " : "Simone",
     " feliz " :  true
    }
)</p>

<p>12. Comando para trazer o retorno de uma forma
mais amigável:</p>

- <p>db.nomeDaCollection.find( ).pretty( )</p>

<p>13. Comando para incluir um registro dentro de uma collection:</p>

- <p>db.nomeDaCollection.insertOne( {atributos} )</p>

<p>Exemplo : db.nomeDaCollection.insertOne( {  "item" :  "cartão" ,  "qtd" :  15  }  )</p>

<p>14. Comando para incluir vários registros de uma única vez:</p>

- <p>db.nomeDaCollection.insertMany( [ { objetos } ] )</p>

<p>O insertMany( ) método possui a seguinte sintaxe:</p>

<p>db.nomeDaCollection.insertMany ( 
   [  < documento  1 >  ,  < documento  2 > ,  ...  ], 
   { 
      " numero " :  56, 
      " ordenado " : true 
   } 
)</p>

<br>

<p>Para informações sobre mais comandos ou informações mais detalhadas e completas, consulte a bíblia abaixo :</p>

[Manual do MongoDB 4.4]( https://docs.mongodb.com/manual/ )

<br>

Referências bibliográficas:

<br>

[Wikipedia](https://pt.wikipedia.org/wiki/Banco_de_dados#Bases_de_Dados_Relacionais)

[Blog Gran Cursos Online](https://blog.grancursosonline.com.br/conceito-de-banco-de-dados/)

<br>

#### Por : Inácia Simone da Silva - Aluna da Turma Back-end Porto-MINAs 2020.2

