# ProjetoBD

Descrição do Projeto:

O projeto é um site de CRUD simples e funcional (utilizando bootstrap para o estilo do site).

Passos a passo para utilizar o site:

1- Baixe o arquivo "ProjetoBD.rar", coloque ele dentro da pasta xampp/htdocs e extraia os arquivos lá;

2- Abra o aplicativo XAMPP e inicie o mysql e o apache;

3- Ainda no aplicativo XAMPP clique  em "admin" na aba do "mysql" e você será redirecionado para o site "php myadmin";

4- No site, clique na aba "importar" e importe o arquivo "CadastroBD.sql";

5- Após fazer isso o banco de dados "cadastro" com a tabela "usuarios" será instalada;

6- Com o banco de dados instalado você pode pesquisar em seu navegador "localhost/ProjetoBD/", assim, abrindo o nosso site de cadastro;

7- Dentro do site vai ter um botão no canto superior direito onde, após o clique, serão mostrados as opções "home,"novo usuário" e "listar usuários";

8- Na página de "novo usário" você será capaz de se cadastrar no site e suas informações serão armazenadas no banco de dados;

9- Com suas informações armazenadas no banco de dados, você poderá ver elas na página "listar usuários";

10- Na página de "listar usuários" você será capar de editar os cadastros feitos no botão "editar" e excluir o cadastros feitos no botão "excluir";

11- Esse é o nosso site de CRUD!

O Banco de Dados:

O banco de dados é muitos simples, com apenas uma tabela chamada "usuarios" e dentro dela, armazenando "id","nome","email","senha" e "data de nascimento", sendo o "id" com auto incremento e a "senha" sendo armazenada com criptografia de md5 para garantir privacidade.
