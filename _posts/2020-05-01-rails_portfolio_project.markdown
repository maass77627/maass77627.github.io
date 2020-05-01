---
layout: post
title:      "Rails Portfolio Project"
date:       2020-05-01 22:52:00 +0000
permalink:  rails_portfolio_project
---


.

This blog is intended as a little helper for anyone heading into their Rails Portfolio project week. It can be very overwhelming knowing where to start. For this project more than any before I would say planning is of the utmost importance. Really putting a lot of effort towards what your project is going to look like how you are going to implement the relationships and nested resources is key before you even start typing a bit of code. If you do not spend a good amount of time laying down the Foundation you are going to run into a lot more problems than you would like. 

Map out your classes and associations. Know where you are going to put that join table and what forms you are going to need this will really save you some time. 

Heres just a few reminders as your going in.

* Dont forget foreign keys go in the table with the belongs_to relationship. 

* make sure you are pluralizing where it is appropriate .. for example...

Migration table: 			dogs
Class: 			Dog
File: 			/app/models/dog.rb
Primary Key: 	id
Foreign Key: 	cat_id
Join Tables: 	dogs_cats

Class: 			DogsController
File: 			/app/controllers/dogs_controller.rb
Views: 		/app/views/dogs.html.erb

etc.

Do your research on accepts_nested_attributes_for
strong params and form_for, fields_for and form_with! 

Hopefully these are just a few helpful tidbits to help you get started on your project journey.. Remember do not skip the planning phase it will be key!! good luck !

