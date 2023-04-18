# E-COMMERCE STORE

## Description
This is an e-commerce store developed using the Ruby on Rails framework and the Solidus gem, which is a popular open-source e-commerce platform built on top of Rails. 

## Features
- User-friendly interface for customers to browse products, add items to their cart, and make purchases. 
- Includes an admin panel for managing products, orders, and customers.

## Please initialize these before starting the app:

### Versions


![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white) 3.0.3p157 (2021-11-24 revision 3fb7d2cadc) [x86_64-linux]

![Ruby on Rails](https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=ruby-on-rails&logoColor=white) 6.1.4.6

### Tools Used

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)
![SASS](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)


### Setup

```
 git clone git@github.com:guavalines/share_a-dog
.git
 cd share_a-dog
 rails db:create db:migrate db:seed:replant
 bundle install
 yarn install
 rails server
```

Open you browser and visit localhost:3000














Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.






### Prerequisites:

Ruby 2.7 or higher
Rails 6.0 or higher
PostgresSQL

Installation:

Clone the repository to your local machine.
Run bundle install to install all required dependencies.
Run rails db:create db:migrate db:seed to create the database, run the migrations, and seed the database with sample data.
Start the server using rails s.
Navigate to http://localhost:3000 in your browser to view the store.

Usage:
Customers can browse products by category, search for specific items, add items to their cart, and checkout. The store includes a secure payment gateway to process credit card payments.

Admin users can manage products, orders, customers, and other store settings from the admin panel. The admin panel is accessible at http://localhost:3000/admin.

Contributing:
If you find any bugs or issues with the store, feel free to open a GitHub issue or submit a pull request with your suggested changes.

License:
This e-commerce store is open-source software released under the MIT License. Feel free to use, modify, and distribute the code as you see fit.
