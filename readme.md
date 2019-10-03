## symfony-swagger-example

Example of usage [harmbandstra/swagger-ui-bundle](https://github.com/harmbandstra/swagger-ui-bundle) and [NelmioApiDocBundle](https://github.com/nelmio/NelmioApiDocBundle) in one Symfony 4 project.

##### Required

- Symfony 4.3.4
- php 7.3.9
- MySQL Ver 14.14

##### Installation

- Clone project
- Run `composer install`
- Create .env.local file and config database connection in it.
(Line `DATABASE_URL=mysql://`)
- Run

    `php bin/console doctrine:database:create`
    
    `php bin/console doctrine:migrations:migrate`
    
- Ok. Run `php bin/console server:start`

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in browser.

Check `http://127.0.0.1:8000/old/api/docs` (swagger-ui-bundle)

Check `http://127.0.0.1:8000/api/docs` (NelmioApiDocBundle)

Profit =)

