# <p align="center">Angular Project</p>

This project is based on a free course available at [cod3r.com](https://www.cod3r.com.br):+1:

:eyes: https://www.cod3r.com.br/courses/angular-9-essencial :eyes:

## <p align="center">About the Project</p>

This project aims to develop a simple CRUD with Angular

## Installing the backend

For the backend json-server was used

Inside the backend folder, run the commands with npm

- npm init -y
- npm install json-server
- config scripts -> "start": "json-server --watch database.json --port 3001"
- npm start

## Installing Angular Cli

- npm install -g @angular/cli

## Creating a new Project

- ng new frontend --minimal

Inside the frontend folder, run the commands with npm

- npm start

## Installing Angular Material

- npm install --save @angular/material @angular/cdk @angular/animations

- ng add @angular/material 

## Creating a Component

- ng generate component "directory were will be created"

or

- ng g c "directory were will be created"

## Creating the header component

Inside the frontend folder, run the commands with npm

- ng g c components/template/header

## Creating the footer component

Inside the frontend folder, run the commands with npm

- ng g c components/template/footer

## Creating the navigation component

Inside the frontend folder, run the commands with npm

- ng g c components/template/nav

## Creating the home component

Inside the frontend folder, run the commands with npm

- ng g c components/views/home

## Creating the products-crud component

Inside the frontend folder, run the commands with npm

- ng g c components/views/products-crud

## Adding the AppRoutingModule

Inside the frontend folder, run the commands with npm

- ng generate module app-routing --flat --module=app

## Creating the product-create component

Inside the frontend folder, run the commands with npm

- ng g c components/product/product-create

## Creating the product Service

Inside the frontend folder, run the commands with npm

- ng g s components/product/product

## Two-way binding

- [(ngModel)]="product.name"
- [(ngModel)]="product.price"

[understading two-way binding](https://angular.io/guide/two-way-binding)

## Creating the product-read component

Inside the frontend folder, run the commands with npm

- ng g c components/product/product-read

## Installing Schematics Form

Inside the frontend folder, run the commands with npm

- ng generate @angular/material:table components/product/product-read

## Creating the product-update component

Inside the frontend folder, run the commands with npm

- ng g c components/product/product-update

## Creating the product-delete component

Inside the frontend folder, run the commands with npm

- ng g c components/product/product-delete

## Creating the header Service

Inside the frontend folder, run the commands with npm

- ng g s components/template/header/header

## Layout

![angular-01](https://user-images.githubusercontent.com/50461475/132263779-9cd76ffd-392e-47bd-8544-7af2dc276e8d.png)

![angular-02](https://user-images.githubusercontent.com/50461475/132263781-692ff5e2-442e-48cb-b37e-2b11d8207ce5.png)
