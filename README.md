<p align="center"><a target="_blank"><img src="https://raw.githubusercontent.com/avored/framework/main/logo.svg" width="400"></a></p>

# Ecommerce Inventory Management System Development for AvoRed

##### Backend APP setup

First thing first we will install laravel backend api service. First thing first we will install the laravel app.

    composer create-project laravel/laravel avored-backend
    cd avored-backend
    composer require avored/framework
    composer require avored/dummy-data
    composer require avored/cash-on-delivery
    composer require avored/pickup

Set up your .env values and CORS

##### Frontend APP Setup

    git clone https://github.com/johncoffeeocean/avored_laravel_react
    cd avored-frontend
    npm install
    npm run serve
