# Golden

Setup

    mix do clean, deps.clean --all
    mix deps.get
    mix compile

## Assets

    cd assets/
    npm install autoprefixer postcss postcss-import postcss-cli tailwindcss --save-dev
    npm install alpinejs
    npm install @tailwindcss/typography
    npm install --save-dev tailwindcss-font-inter

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Install authentication from [https://github.com/aaronrenner/phx_gen_auth](https://github.com/aaronrenner/phx_gen_auth).

    mix phx.gen.auth Accounts User users


Add Inter font from [https://elixirforum.com/t/phoenix-1-6-0-liveview-esbuild-tailwind-jit-alpinejs-a-brief-tutorial/41669/6](https://elixirforum.com/t/phoenix-1-6-0-liveview-esbuild-tailwind-jit-alpinejs-a-brief-tutorial/41669/6)