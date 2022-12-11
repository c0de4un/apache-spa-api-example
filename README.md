# apache-spa-api-example
Sample apache config for api and spa

App is working on PHP with CodeIgniter framework 4

[![GitHub license](https://img.shields.io/github/license/c0de4un/apache-spa-api-example)](https://github.com/c0de4un/apache-spa-api-example/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/c0de4un/apache-spa-api-example)](https://github.com/c0de4un/apache-spa-api-example/stargazers)

## About setup
App runs on Apache 2.4 with PHP 8.2. Database is MySQL 8

## Installation
1. Run
```sh
    docker-compose up --build -d
```
2. Download composer.phar to `app/html/api`
3. Install CodeIgniter Framework
```sh
    $cd app/html/api
    $php composer.phar install
```