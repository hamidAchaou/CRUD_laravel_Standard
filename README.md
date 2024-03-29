# Laravel Standard CRUD Operations with AdminLTE

This repository demonstrates a standard CRUD (Create, Read, Update, Delete) operations setup using Laravel along with the AdminLTE template.

## Installation of AdminLTE

```bash
npm install admin-lte@3.1 --save

```
```bash
    npm run dev
```
 - Importez dans resource\css\app.css
```bash
    @import 'admin-lte/dist/css/adminlte.min.css';
    @import 'admin-lte/plugins/fontawesome-free/css/all.min.css';
    @import 'admin-lte/dist/css/adminlte.min.css';
    @import 'admin-lte/plugins/fontawesome-free/css/all.min.css';
    @import 'admin-lte/plugins/icheck-bootstrap/icheck-bootstrap.min.css';
    @import 'admin-lte/plugins/jqvmap/jqvmap.min.css';
    @import 'admin-lte/plugins/tempusdominus-bootstrap-4/css/tempusdominus-bootstrap-4.min.css';
    @import 'admin-lte/plugins/overlayScrollbars/css/OverlayScrollbars.min.css';
    @import 'admin-lte/plugins/daterangepicker/daterangepicker.css';
    @import 'admin-lte/plugins/summernote/summernote-bs4.min.css';
```
 - Importez dans resource\js\app.js
```bash
    import './bootstrap';
    import 'admin-lte';
```
 - Ajoutez la ligne suivante à la section <head> dans layouts.layouts
```bash
    @vite(['resources/css/app.css', 'resources/js/app.js'])
```

## Créez le modèle, le contrôleur, la ressource, la migration, la requête et le seeder

 - Projects
 ```bash
    php artisan make:model Projects -mcrRs
 ```
  - Tasks
 ```bash
    php artisan make:model Projects -mcrRs
 ```

 ## Exécutez la migration et le seeder
 - Migration 
 ```bash
    php artisan migrate
 ```
 - Seeder 
 ```bash
    php artisan db:seed
 ```

## Exécutez le serveur
```bash
    php artisan serve
``` 