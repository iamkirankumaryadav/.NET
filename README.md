<p align=right><a href='https://github.com/KIRANKUMAR7296/SQL'>Navigate to SQL</a></p>

### What is MVC ?

- `MVC` : Model `Data` + View `UI` + Controller `Brain`
- Core concept is to separate the `business logic`, `user interface` and `data model` from each other.
- `Model` : A model extracts data from a database like `cloud`, `local storage`, `API's`
- `View` : View represents the `UI` of app, it shows the data model and takes inputs from the users.
- `Controller` : Consist of `business logics`, control and decide what will be displayed to user.
- `MVC` helps to make work easy, structured and organized.
- So if something is changed in one part of the project, it will not affect other parts of the project. 
- User interacts with `view` on which data is displayed and provide input with `controller` through `view`
- `Controller` is like brain it manipulates the data for user or take data from `model` to work.
- And after work is completed again it is provided back to `view` which shows desired data to users.

### Can we use Multiple web.config file ? : `Yes`

- We have one main configuration file : `Web.Config`
- Then we have two more configuration files : `App.Config` and `Database.Config`
- `App.Config` :  Here we define all the application level settings ( Protocol, Request, Response )
- `Database.Config` : Here we define all the database level settings ( Data Source, Password )

```c#
<appSettings configSource="app.config">
</appSettings>
<connectionStrings configSource="database.config">
</connectionStrings>
```

ASP.NET Full Stack Developer

`Front End` : `HTML`, `CSS`, `JavaScript`, `Bootstrap` (CSS library) and `jQuery` (JavaScript library)

`Back End` :  `C#` programming language

`Framework` : `ASP.NET`

`Database` :  `SQL`


