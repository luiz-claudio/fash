## DESCRIÇÃO

Componente Vue para mostrar flash mensagem.


## INSTALAÇÃO

1. composer require lsiqueira/flash

2. Importar a a lib no PROVIDER(config/app.php)
   
    'providers' => [
        lsiqueira\fash\LazinessServiceProvider::class,
    ]

3. Publicar o componente VUE:

    php artisan vendor:
    
4. Rodar o npm:

    * npm install
    * npm run dev


5. Importar em resources/js/app.js
   
    Vue.component('flash', require('./components/flash.vue').default);

6. Exemplo usando na view

# tipo 1 == sucess tipo 2 == alert

<flash message="ola mundo"
     tipo=1>
</flash>




