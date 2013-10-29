# Oauthex
A wrapper around [erlang-oauth](https://github.com/tim/erlang-oauth) for [elixir](http://elixir-lang.org/).

# Example
See `bin/twitter.mxs` for a quick example. To use this script:

```console
elixir --erl '-pa ebin deps/*/ebin' bin/twitter.mxs <consumer_key> <consumer_secret>
```

You will see an url, hit it with your browser and authorize the app. Then execute
the command shown:

```console
elixir --erl '-pa ebin deps/*/ebin' bin/twitter.mxs <consumer_key> <consumer_secret> <request_token> <request_secret> <authorization PIN>
```

Trying the *track* in the twitter streaming api:

```console
elixir --erl '-pa ebin deps/*/ebin' bin/twitter.mxs <consumer_key> <consumer_secret> <request_token> <request_secret> track <word>
```

# License
This software is under the Apache 2 License. See the **LICENSE** file for more details.
