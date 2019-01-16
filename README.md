# Intrica Code Challenge
This coding challenge is designed to test your ability to work with PDO and SQL Queries
from within PHP. Within the `Main` class there are several empty method bodies and some comments detailing
what each method should do.

There are a few unit tests included in this repo which will double check your code to make sure it fulfills
the criteria - You can run these yourself if you like by calling `composer test` on the command line.

Once you've finished and you're confident you have completed the code challenge push your code to your repository/fork
and send Mark an email (`mark@intrica.net`) - We'll check it over and get back to you with some feedback.

## Installation & Setup
 
 - Make a fork of this repository

 - Install MySQL (if it's not already installed), run the .sql file included in this repo to create a database called `intrica-code-challenge`
 complete with a dummy data set you'll be building functionality to run queries on.
 
 - Install dependencies using Composer (if you don't have Composer installed on your machine there's a guide 
 on the [official docs](https://getcomposer.org/doc/00-intro.md))
 ```
    composer install
```
 
 - Make a copy of the `database.config.php.dist` file located in the `config` directory and rename the copy to `database.config.php`, Adjust the values to match your local machine's database setup 
 
 - Start up a PHP server so you can see the results of your work, if you're using PHPStorm we've included our `.idea` which has a run config already setup 
 ```
    php -S 0.0.0.0:8080 -t public
 ```
 
 - Navigate to [localhost:8080](http://localhost:8080) and you should see a blank table with a few table headings
 
 - Open the `Main` class (located in `src/Main.php`) and write some method bodies that fulfill the requirements given in the comments