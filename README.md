# Chirps - Projeto Laravel

Este é um projeto Laravel chamado "Chirps" que utiliza PHP 8.2 e SQLite como banco de dados.

## Passos para Rodar o Projeto

Siga os passos abaixo para executar o projeto em sua máquina local:

### 1. Clonar o Repositório

Clone o repositório do GitHub em seu ambiente de desenvolvimento:

```bash
git clone https://github.com/seu-usuario/chirps.git
```

### 2. Instalar Dependências

Certifique-se de estar no diretório do projeto e execute o comando composer install para instalar todas as dependências do Laravel:

```bash
cd chirps
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

### 5. Iniciar o Servidor

Inicie o servidor de desenvolvimento local:

```bash
php artisan serve
```

### 6. Acessar o Projeto

Abra o seu navegador e acesse o projeto no seguinte endereço:

```arduino
http://localhost:8000
```
