
# Comandos para configurar o projeto Laravel (passo a passo único)

# 1. Acesse este repositório no GitHub e clique no botão **Fork** no canto superior direito da tela.

# 2. Clonar o repositório do seu fork
```bash
git clone  https://github.com/seu-usuario/Laravel-AdminPage.git 
cd nome-do-repositorio
```

# 3. Instalar as dependências PHP
```bash
composer install
```

# 4. Copiar o arquivo de ambiente
```bash
cp .env.example .env
```

# 5. Gerar a chave da aplicação
```bash
php artisan key:generate
```

# 6. Editar manualmente o arquivo .env e configurar o banco de dados
# (exemplo)
```dotenv
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nome_do_banco
DB_USERNAME=usuario
DB_PASSWORD=senha
```

# 7. Rodar as migrations
```bash
php artisan migrate
```

# 8. (Opcional) Rodar os seeders
```bash
php artisan db:seed
```

# 9. Iniciar o servidor local
```bash
php artisan serve
```

# 10. (Se houver frontend com Vite) Instalar dependências e rodar
```bash
npm install
npm run dev
```

# 11. (Opcional) Executar os testes
```bash
php artisan test
```
