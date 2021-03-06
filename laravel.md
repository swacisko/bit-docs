# Laravel

**Prerequisite knowledge:** php, oop, mysql, html, frameworks, mvc, composer, dependency managment

## Intro
Laravel is a free, open-source PHP web framework, created by Taylor Otwell and intended for the development of web applications following the model–view–controller (MVC) architectural pattern and based on Symfony. Some of the features of Laravel are a modular packaging system with a dedicated dependency manager, different ways for accessing relational databases, utilities that aid in application deployment and maintenance, and its orientation toward syntactic sugar. [[Source](https://en.wikipedia.org/wiki/Laravel)]

## Classification / acceptance questions

### Apprentice aka _My First TODO app_
* I can Create, Read, Update and Delete entries in DB through Eloquent Model (M in MVC)
* I can create simple blade templates to separate presentation layer from business logic (V in MVC)
* I can use Laravel router to respond to client requests (C in MVC)

### Intermediate aka _Beta users can use my TODO app_
**Prerequisite knowledge:** cookies, session, authorization
* I can use Artisan CLI for DB migration and code generation
* I can set data in users session
* I can introduce Authentication and Authorization to my application using Laravel Policies and Gates to limit allowed actions on a different parts of the application
* I can set Eloquent relations to fetch related data from DB
* I can validate user input to make sure the incoming data is in the expected shape
* I can assign roles with a specific permissions set to users
* I can serve static assets like CSS and JS to make user experience better

### Advanced aka _My TODO app has REST API_
**Prerequisite knowledge:** rest, http
* I can read headers from a request and set headers on a response
* I can create REST API in my app
* I can use Laravel transformers to make the output consistent

### Master aka _My TODO app on production_
**Prerequisite knowledge:** cache, webservers, tests, queues, deployment
* I can introduce cache for Models to avoid performance problems
* I can cache content in the browser to improve user experience
* I can use Jobs, Queues and Scheduler for maintenance or writing asynchronous code
* I can use Dependency Injection design pattern to make the code unit testable 
* I can test my code using Unit Tests and Acceptance Tests
* I can deploy my code to production

## Sources

### Books
- [Laravel: Up & Running: A Framework for Building Modern PHP Apps](https://laravelupandrunning.com/)

### Video
- [Laravel 5.7 From Scratch](https://laracasts.com/series/laravel-from-scratch-2018)

### Read online
- [Laravel Tutorial: Step by Step Guide to Building Your First Laravel Application](https://laravel-news.com/your-first-laravel-application)
- [Laravel official docs](https://laravel.com/docs/)
