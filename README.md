## Akvelon test task ([Requirments](https://docs.google.com/document/d/1yCVTrXE_T_vx0MVKxdBwAX7jpuPomXxQqLtrAnqIhc8/edit#heading=h.aggrycwiy8fe))

### Technologies:
* .NET 5.0
* ASP NET Core
* PostgreSQL
* EF Core
* Heroku

### Architecture: 
* Three-layer (Business Logic, Data Access, Representation)
* DDD stuff

### Patterns and other goods:
* State
* Specification
* Either monad

### How to use:
Just go to the [site](https://akvelon-test-task-app.herokuapp.com/swagger/index.html) or if you want it on your local machine you can clone repo and run with Rider, VS or other IDE

### About filters:
I think in real project queries would be compiled automatically with UI and JS for example. So I decided to make query language not so user friendly but multifunctional. For example if you want to get **tasks with Priority greater than Normal or Status equal to ToDo** you should send following query `priority>normal&status=todo`.
