# Trello Clone Base

This project was created watching and following this [video](https://www.youtube.com/watch?v=pRybm9lXW2c)

## To run it

- Copy `.env.example` and rename to `.env`
- Create a `clerk` account
- Create an `unsplash` account
- Create a `stripe` account
- Fill the values needed in `.env`
- Run `npm i`
- Run `npm run dev`

### Comments

- I used `supabase` as the DB with `postgresql` so its possible that adding `?pgbouncer=true` to the `DATABASE_URL` is needed
