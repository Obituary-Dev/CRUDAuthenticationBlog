# CRUDAuthenticationBlog
 
## Tools

- composer
- artisan **to create controllers, migrations** 
- eloquent **to obtain an object-relational mapper (ORM) to interact with the database**
- ckeditor **to add a text editor to a textarea**
- tinker **to interact with the database**
- laravel/collective **to help making forms**
- laravel ui + ui vue --auth **to create a registration feature**

## Command lines

- composer create-project laravel/laravel ProjectName
- php artisan make:controller ControllerName
- php artisan make:model Post -m **to make a model with a migration** 
- php artisan tinker
- php artisan make:controller PostsController --resource
- composer require laravelcollective/html
- php artisan route:list
- composer require laravel/ui
- php artisan ui vue --auth
- php artisan make:migration add_user_id_to_posts
- php artisan migrate

## Tips 

Configure providers for laravel collective in config/app.php: 
    Collective\Remote\RemoteServiceProvider::class,

Configure aliases for laravel collective in config/app.php: 
        'Form' => Collective\Html\FormFacade::class,
        'Html' => Collective\Html\HtmlFacade::class,

.env enables to change title of the app 

.env enables to set database parameters


