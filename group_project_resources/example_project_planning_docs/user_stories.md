# User Stories

## Users

### Sign Up

* As an unregistered and unauthorized user, I want to be able to sign up for the website via a sign-up form.

### Log in

* As a registered user, I want to be able to log in to the website via a log-in form with the credentials i signed up with.


### Demo User

* As someone without an account just looking to try out the site, I'd like to be able to log in quickly via a clearly marked "demo user" button on an ever-present navbar

### Log Out

* As a logged in user, I'd like to be able to log out in order to prevent access to my account by anyone that may have access to my machine


## Ingredients

* As a user with lots of recipes, I'd like to be able to create a list of ingredients for a particular dish via a form 
    * the form should have however many fields I like, one for each ingredient I have in mind
    * the form should have a submit button available after the final field
    * each ingredient field should provide me with a variety of options
        * I should be able to specify whether I want to record the measurements by volume or mass
        * I should have a variety of units at my disposal
        * volume
            * tsp
            * tbsp
            * ml
            * L
        * mass
            * g
            * kg

* As a user trying to remember the ingredients for a particular dish, I'd like to be able to view them
    * I should be able to scale the entire recipe based on the quantity of a particular ingredient that I have on hand
    * I should be able to scale the entire recipe based on the total mass/volume that I want to yield

* As a user that updates makes mistakes frequently, I'd like to be able to edit my ingredient specifications via the same form I created them with

* As a user that occasionally moves on from recipes, I'd like to be able to delete them

## Procedure

* As a user that is only human, I'd like to be able to optionally describe in detail the general steps required to execute a complicated dish
    * I'd like to be able to use a large rich text field to create a procedure in as many words as I'd like

* As a user that is prone to forgetting, I'd like to be able to optionally view the procedure on the same page as the ingredients

* As a user that makes mistakes occasionally, I'd like to be able to edit the procedure via the same rich text field

* As a user that is paranoid about their secret tricks being stored online, I'd like to be able to delete the procedure
