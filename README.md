# Chirps - Projeto Laravel

Este é um projeto Laravel chamado "Chirps" que utiliza PHP 8.2 e SQLite como banco de dados.

O Chirper é uma plataforma simples para compartilhar pensamentos e atualizações com seguidores. Ele permite criar, editar e excluir "Chirps" e envia notificações por e-mail para novos Chirps.
Principais Recursos:
* Crie e compartilhe "Chirps".
* Edite e exclua suas postagens.
* Receba notificações por e-mail de novos Chirps.

### 1. Clonar o Repositório

Clone o repositório do GitHub em seu ambiente de desenvolvimento:

```bash
git clone https://github.com/DukaSiqueira/chirper.git
```

### 2. Instalar Dependências

Certifique-se de estar no diretório do projeto e execute o comando composer install para instalar todas as dependências do Laravel:

```bash
cd chirper
composer install
```

### 3. Configurar o arquivo .env

Copie o arquivo .env.example para .env e configure-o para usar o SQLite como banco de dados. Abra o arquivo .env e configure a seguinte linha:

```plaintext
DB_CONNECTION=sqlite
```

### 4. Executar as Migrações

Execute as migrações para criar as tabelas do banco de dados:

```bash
php artisan migrate
```

### 5. Gerar a chave da aplicação

Execute o comando para gerar a chave da aplicação:

```bash
php artisan key:generate
```

### 6. Iniciar o Servidor

Inicie o servidor de desenvolvimento local:

```bash
php artisan serve
```

### 7. Acessar o Projeto

Abra o seu navegador e acesse o projeto no seguinte endereço:

```arduino
http://localhost:8000
```
### 7. Utilizar o projeto

No canto superior direito, contém duas urls. Uma para login e outra para registrar-se. <br>
Após o login é só navegar de Dashboard para Chirps e começar a utilizar.
O chirper conta com recursos de criar, editar e excluir, assim como conta com um mecânismo de envio de e-mail assim que novs chirps são criados.
Para utilizar o mecânismo de notificação de email, leia a documentação do laravel. <br>
https://laravel.com/docs/10.x/mail#introduction
