## Deployment

- Com o GIT instalado, em seu terminal, clone o projeto em uma pasta: **git clone https://github.com/grdsenai/adminpanellaravel.git .**
- Copie **.env.example** para um novo arquivo chamado **.env** e ajuste as credenciais do banco de dados.
- Rode o comando **composer install** em seu terminal
- Rode o comando **php artisan migrate --seed**<br>
-- Aviso: os seeders são importantes, pois eles vão criar os registros necessários para poder utilizar o usuário padrão no login.
- Rode o comando **artisan key:generate**.
- Se possuir upload de arquivos/fotos no seu projeto é necessário rodar o comando **php artisan storage:link**
- Inicialize o servidor rodando o comando **php artisan serve** e posterior acesse http://localhost

## Default credentials

**Username:** admin@admin.com<br>
**Password:** password

## Created by

[Quick admin panel](https://quickadminpanel.com)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

