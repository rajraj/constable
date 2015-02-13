# Constable API

Constable API uses Phoenix Channels to make a real time connection to the
Constable front end.

## Starting Constable

1. Run `bin/setup` to install dependencies and setup the database. This is
idempotent. Run whenever you like.
2. Start Phoenix endpoint with `mix phoenix.server`

Now you can visit `localhost:4000` from your browser.

## Testing

1. Run `mix test`

## Using the Constable API

Visit the [thoughtbot/constable repo](http://github.com/thoughtbot/constable) to
see how to use the API.
The [app/stores](https://github.com/thoughtbot/constable/tree/master/app/stores)
folder has a few the best examples.

## Deployment

1. If you have not run `bin/setup` yet, run it to add the correct git remotes.
2. Run `bin/deploy (staging|production)`