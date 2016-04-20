# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
To support the front end of the application that the user interacts with by providing the user with requested data/information from the sever.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The model.
```

Which layer in the MVC pattern communicates with the model?

```bash
The controller.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Because it is used primarily in multi page web pages rather than SPAs and is a more slow/inefficient way of displaying information.
```

What does C.R.U.D stand for?

```bash
Create, read, update, destroy.
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
The model.
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
Index, create, show, update, destroy.
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
-- The front end triggers a GET request, most likely via uSer interaction
-- The GET request is recieved by the server
-- The back end assesses the request and determines what data is being requested
-- The requisite data is retrieved
-- The data is converted into JSON format and sent back to the front end/user
```

What is the command to generate a new rails-api app?

```bash
rails-api new <app_name> --database=postgresqul
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
-- db:drop
-- db:create
-- db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
// your response here
```

List two advantages of using serializers? (2 bullet points)

```bash
-- They specify what JSON to send
-- They allow objects to be passed through HTTP to a web service.  
```
