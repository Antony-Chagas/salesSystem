# Sistema de vendas 🛍️

Projeto para processo seletivo da vaga de programador Junior na empresa Tray.

## Indice
* [Índice](#índice)
* [Descrição do Projeto](https://github.com/Antony-Chagas/salesSystem/blob/main/README.md#descri%C3%A7%C3%A3o-do-projeto-)
* Tecnologias utilizadas
* Funcionalidades do projeto
* Como de usar a aplicação
* Banco de dados
* Paginas do projeto
  

## Descrição do Projeto 📰
* Sistema para cadastro de vendas para vendedores.
* Sistema desenvolvido para ajudar e facilitar o controle das vendas, podendo incluir vendas para seus respectivos vendedores, além de conseguir atualizar, visulizar e excluir vendas e vendedores.
  ![image](https://github.com/Antony-Chagas/salesSystem/assets/104728389/e7b874e8-48f2-4e88-a502-e6274d95390e)

## Tecnologias utilizadas 🖥
* **XAMPP** Foi utilizada a versão 3.3.0, utilizado para ativar o servidor local e uso do PHP e banco de dados.
* **PHP 8:** Foi utilizada a versão  PHP 8.2.12, utilizado para criação do do BackEnd do projeto.
* **bootstrap:** Foi utilizada a versão 4.5, utilizado para configuração do front, deixando o sistema mais funcional e mais profissional
* **MySQL:** Banco utilizado na aplicação.
* **Composer:** Ultilizado para instalação do Framework laravel
* **Framework laravel** Foi utilizada a versão 11x.

## Funcionalidades do projeto 🛠️

* Criar, deletar, atualizar e visualizar vendas realizadas.
* Criar, deletar, atualizar e visualizar vendedores.

## Como de usar a aplicação ⚙️

### O que deve ter na sua máquina:
* **XAMPP**: Você pode fazer o download pelo link https://www.apachefriends.org/download.html <br>
  Após fazer a instalação acesse a pasta C:\xampp\php\php.ini e habilite `extension=pdo_mysql`, basta apenas remover o ";"
  ![image](https://github.com/Antony-Chagas/salesSystem/assets/104728389/ce1e5437-e1ba-49ee-9a5b-0e04e6b8351f)

* **Editor de código**: O que foi utilizado no desenvolvimento foi Visual Studio Code, download https://code.visualstudio.com/download
* Acesse o XAMPP e ligue o Apache e MySQL
  
 ![image](https://github.com/Antony-Chagas/salesSystem/assets/104728389/f5fe1b87-6776-4039-8fb7-8e9220469452)

* Instale o laravel como o comando:
~~~php
composer create-project laravel/laravel example-app
~~~ 
* Ative o servidor do laravel como o comand:
~~~php
php artisan serve
~~~
    
## Banco de dados
* Crie um novo banco de dados (Acesse o banco pelo XAMPP, na linha MySql clique em Admin).
* Configure a conexão com o banco de dados no arquivo .env localizado na raiz do projeto. Exemplo de configuração:
* Execute as migrações do banco de dados para criar as tabelas necessárias.

## Paginas do projeto





