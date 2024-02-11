# My first project with Ruby on Rails

This is a simple project i made, while learning the basics of RoR, following the MVC structure.

## Built With

- Ruby version 3.3.0
- Ruby on Rails version 7.1.3
- SQLite3
- TailwindCSS v3.4.1 (Play CDN)

## Notes for CLI Commands learned through the project

### Start server (local)

```cli
rails s
```

### Generate route (controller)

```cli
rails g controller <route>
```

### Generate db-table (model)

Types of data that can be used:

- string
- text
- integer
- float
- decimal
- boolean
- binary
- date
- time
- datetime
- timestamp

```cli
rails g scaffold <table_name> <table_column>:<data-type>
```

Example:

```cli
rails scaffold user first_name:string last_name:string email:string phone:string
```

To push the new migration file generated, use following command:

```cli
rails db:migrate
```

## Credits

- [Tutorial by freecodecamp.org](https://freecodecamp.org/)
- [Video tutorial used from freecodecamp.org](https://www.youtube.com/watch?v=fmyvWz5TUWg)