# Introduction

This project is to grab data from your 

# Usage

Just connect to your project domain with your yahoo fantasy league id for example `https://YOURDOMAIN.com/1234`.

# Init project

### Init project
copy the .env.example to .env, and execute `php artisan key:generate`.

### Init database

Init sqlite in root path, or anywhere you want, change the path to .env file.

```
sqlite3 database.sqlite "VACUUM;"
```
