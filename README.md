# Community

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.create && mix ecto.migrate`
  * Start Phoenix endpoint with `iex -S mix phx.server`

Now you can visit [`http://localhost:4000/graphiql`](http://localhost:4000/graphiql) from your browser.

Play around! :)

Some examples:

#### Get all links

```
{
  allLinks {
    id
    url
    description
  }
}
```

#### Create a new link

```
mutation {
  createLink(
    url: "http://npmjs.com/package/graphql-tools",
    description: "Best Tools!",
  ) {
    id
    url
    description
  }
}
```


## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: https://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix
