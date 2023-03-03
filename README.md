# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## usersテーブル

|Colum              |Type      |Option      |
|-------------------|----------|------------|
|name               |string    |null:false  |
|email              |string    |null:false  |
|encrypted_password |string    |null:false  |

### Association



## recipesテーブル
|Colum              |Type      |Option      |
|-------------------|----------|------------|
|recipe_name        |string    |null:false  |
|genre              |string    |null:false  |
|food               |string    |null:false  |
|quantity           |string    |null:false  |
|content            |string    |null:false  |


