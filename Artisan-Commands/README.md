## Artisan Commands
//==============================================================
### Migrations

#### Run pending migrations
php artisan migrate

#### Rollback the last database migration
php artisan migrate:rollback

#### Create a new migration file
php artisan make:migration CreateTableName

#### Change Existing Table column type

###### Install doctrine:
`composer require doctrine/dbal`

###### Make Migration file:
`php artisan make:migration change_(Column_name)_type_in_(table_name)`


### Seeders

#### Run database seeders
`php artisan db:seed`

#### Generate a seeder class
`php artisan make:seeder SeederClassName`

### Tinker (Interactive Shell)

#### Enter the Tinker interactive shell
`php artisan tinker`

#### Execute arbitrary PHP code