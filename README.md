# Rocketpay

This is a small application to practice and learn more about Elixir and your framework Phoenix, isn't recommended to use this application in production.  
  
This application have as functionality create user, make deposit, make withdraw and make transactions between accounts createds.

### Technologies  
- Elixir
- Phoenix framework
- PostgreSQL  
  
### Fill `.env`  
Is required create and to fill `.env` at path `./config/.env`, has a sample file called `.env.example` at path `./config/.env.example` to use as base to create and to fill `.env` file:  
  
```
export USERNAME_BASIC_AUTH='USERNAME_BASIC_AUTH'
export PASSWORD_BASIC_AUTH='PASSWORD_BASIC_AUTH'
export BASIC_AUTH_ENCODED='BASIC_AUTH_ENCODED'
export HOST='HOST'
export SECRET_KEY_BASE='SECRET_KEY_BASE'
export SIGNING_SALT='SIGNING_SALT'

export DB_USERNAME='DB_USERNAME'
export DB_PASSWORD='DB_PASSWORD'
export DB_NAME='DB_NAME'
export DB_HOST='DB_HOST'
```  
  
To use `.env` is required run source on file with command `source .env`.

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix
