# Teste Prático Desenvolvedor(a) PHP Júnior
Projeto de CRUD do processo seletivo ACS Laboratórios para Desenvolvedor PHP Jr.

# Requisitos
 - PHP 7 ou superior
 - MySQL 
 - Composer (Gerenciador de dependências, mas nesse projeto é responsável pela configuração de autoload das classes)
 - Xampp (APACHE e MySQL) ou similar

# CRUD-php-ACSLabs
 APP simulando um site de divulgação de vagas de emprego da empresa, feito com CRUD - utilizando PHP orientado a objetos, PDO e MySQL.

# Passo a Passo
- Primeiro passo: Clone este repositório com o link https://github.com/kiq-caique/CRUD-php-ACSLabs.git;
- Segundo passo: Criar o Banco de dados, utilizei o Xampp e com o APACHE (PORT:80) e MySQL (PORT:3306) acesse o phpMyAdmin (http://localhost/phpmyadmin/index.php)
e crie um banco de dados, e dentro dele, uma tabela chamada "vagas" com os seguintes campos: (tabela/imagem abaixo);


![image](https://user-images.githubusercontent.com/96061515/233449049-96c6768e-a63e-48cf-98b3-f09654a1e644.png)                                        

![image](https://user-images.githubusercontent.com/96061515/233446192-87e88ded-846b-4683-a7b9-b9f877798ede.png)


- Terceiro passo: No mesmo banco de dados, crie uma nova tabela com nome de "users" com os campos de "id" (igual ao id da tabela "vagas"), "email" (VARCHAR) e "senha" (INT);
- Quarto passo: Insira um usuário na tabela "users";
- Quinto passo: acesse o http://localhost/acslab/index.php para acessar a pagina de login;
- Sexto passo: insira os dados do usuário criado na tabela "users" na pagina de login (imagem);

![image](https://user-images.githubusercontent.com/96061515/233451853-02f33eae-fd93-426a-92f6-de225c24e4f3.png)

- Sétimo passo: Após inserir os dados e clicar em "Entrar", você será como um administrador reponsável pelas publicações de vagas, podendo:
  
  Criar 
  ![image](https://user-images.githubusercontent.com/96061515/233452152-3db985ad-728f-4041-b758-b47f93508890.png)

  Editar
  ![image](https://user-images.githubusercontent.com/96061515/233453257-e947de0c-a956-4629-8497-7adb2445a11c.png)
  
  Excluir as vagas
  ![image](https://user-images.githubusercontent.com/96061515/233453641-34642a48-b7e5-43cc-b843-d056fd87a6ee.png)





