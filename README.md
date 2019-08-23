# Groupletter

## Start developing

### Install

- [Homestead](http://laravel.com/docs/5.0/homestead) and setup for this project
- [Node](http://nodejs.org/download/) (version 0.10.x)

### Run

- Setup [environment configuration](http://laravel.com/docs/5.0/configuration) file `.env`. See `.env.example`.

#### In dev environment in project root (Homestead):
- `composer install`
- `php artisan migrate`
- `php artisan db:seed`

#### On local machine in project root:

##### If starting development for the *first time*
- `sh setup` or `./setup`
- `gulp watch` (while developing)

##### If you have bower and gulp *already installed*
- `sh setup -u` or `./setup -u`
  - Both -u and --update work.
  - This option skips the gulp and bower base install, and just runs package installation.
- `gulp watch` (while developing)

You can now visit the site locally (depends on your Homestead settings) and login with admin@groupletter.io / admin
