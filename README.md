# Rocketpay

API created during the NLW #04

## Requirements

- Elixir
- Phoenix
- PostgreSQL

## Running the project

Install dependencies:
```bash
mix deps.get
```

### Database

The database used for this project is PostgreSQL.

You can run this through docker using the command below, then setup the database:
```bash
docker run --name rocketpay_pg -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres
mix ecto.setup
```

Run the server:

```bash
mix phx.server
```

Check if the server is up using the [🔗Dashboard](http://localhost:4000/dashboard)

## Tests

Unit tests are inside the `test` folder and can be ran using the command:

```bash
mix test
```

## License

This project is under the MIT license.

---
Feel free to contact me [@abnersajr](https://www.linkedin.com/in/abnersajr/)