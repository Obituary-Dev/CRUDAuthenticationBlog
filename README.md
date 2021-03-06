# CRUDAuthenticationBlog
 
# Tools

- composer
- artisan **to create controllers, migrations** 
- eloquent **to obtain an object-relational mapper (ORM) to interact with the database**
- ckeditor **to add a text editor to a textarea**
- tinker **to interact with the database**
- laravel/collective **to help making forms**
- laravel ui + ui vue --auth **to create a registration feature**

# Command lines

- composer create-project laravel/laravel ProjectName
- php artisan make:controller ControllerName
- php artisan make:model Post -m **to make a model with a migration** 
- php artisan tinker
- php artisan make:controller ControllerName --resource
- composer require laravelcollective/html
- php artisan route:list
- composer require laravel/ui
- php artisan ui vue --auth
- php artisan make:migration MigrationName
- php artisan migrate
- php artisan storage:link **to create public/storage folder and link it to storage/public to make it accessible to the browser**
# Tips 

- Configure providers for laravel collective in config/app.php: 
        Collective\Html\HtmlServiceProvider::class,

- Configure aliases for laravel collective in config/app.php: 
        'Form' => Collective\Html\FormFacade::class,
        'Html' => Collective\Html\HtmlFacade::class,

- .env enables to change title of the app 

- .env enables to set database parameters

# Added folders and files 
------------------------------------------------------------------------------------------------------------------
- views: 

## Folders and all files inside them

- inc 
- layouts 
- pages
- posts 
- auth (made authomatically)
------------------------------------------------------------------------------------------------------------------
- database:

## Folders and some files inside them 

- migrations: 

### Files added 
- 2021_03_05_203608_create_posts_table.php
- 2021_03_06_154048_add_user_id_to_posts.php
- 2021_03_07_122119_add_cover_image_to_posts.php
------------------------------------------------------------------------------------------------------------------