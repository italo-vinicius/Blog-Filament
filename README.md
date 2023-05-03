### Blog Utilizando Filament    

Este é um projeto de blog criado usando o framework Laravel e o pacote Filament para o painel de administração.

O objetivo deste projeto é fornecer uma plataforma para criar e gerenciar conteúdo em um blog de maneira fácil e eficiente.

Tecnologias utilizadas:
- Laravel 10.8
- PHP 8.1^
- Filament 2.17^
- Tailwind

---

## Instalação
Clone este repositório em sua máquina local.

Abra um terminal na pasta raiz do projeto e execute o comando `composer install` para instalar as dependências do Laravel.

Crie um arquivo .env na raiz do projeto. Você pode copiar o arquivo .env.example e renomeá-lo. Configure as variáveis de ambiente do banco de dados nesta etapa.

Execute o `comando php artisan migrate` para criar as tabelas do banco de dados.

Execute o `comando php artisan db:seed` para popular o banco de dados com dados de teste.

Execute o `comando php artisan serve` para iniciar o servidor local.
