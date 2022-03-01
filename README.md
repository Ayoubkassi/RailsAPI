# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

## Dependencies

**gem install mysql2**

after go to gemfile and delete gem "sqltite3" and add gem "mysql2"

and then change in database.yml , into mysql2 , add username and password

and then just run the server using : rails s

## 2 start geneting the Model

using : rails g model Article title:string , price:int , city:string

rails g model Article title:string body:text

rails db:migrate

gem install faker
bundle install

to commit changes in seed : rails db:seed
---
add faker , for fake data , and run bundle install to install dependencies
