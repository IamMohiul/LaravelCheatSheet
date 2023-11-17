## Database
//==============================================================
### Eloquent Models

#### Create a new Eloquent model
`php artisan make:model ModelName`

#### Create a new migration and model
`php artisan make:model ModelName -m`

### Database Operations

#### Create a new database migration
`php artisan make:migration create_table_name`

#### Rollback the last database migration
`php artisan migrate:rollback`

#### Refresh the database and run all seeders
`php artisan migrate:refresh --seed`