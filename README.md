
Setup guide:

1- Create `testdb1` database and import `db.sql` file. Add mysql credentials to `.env` file.

2- run
```
composer install
npm install
npm run prod
```

3- run

`php artisan serve`

in project directory and the application will be available on `127.0.0.1:8000`


Currency rates are cached for 5 minutes. This amount of time can be changed in `.env` file according to manager's decision.
