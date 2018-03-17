## About the project

This project is a simple configuration to work with Laravel on docker.

## How to config this project on your machine
<ol>
  <li>Clone the repository</li>
  <li>Cd into the folder</li>
  <li>Terminal: docker-compose run app composer install</li>
  <li>Rename the file .env.example to .env</li>
  <li>Terminal: docker-compose run app php artisan key:generate</li>
  <li>Change the following lines inside the .env file:
    <br>
    DB_CONNECTION=pgsql
    <br>
    DB_HOST=database
    <br>
    DB_PORT=5432
    <br>
    DB_DATABASE=Your-database-name
    <br>
    DB_USERNAME=postgres
    <br>
    DB_PASSWORD=Your-password
  </li>
</ol>
