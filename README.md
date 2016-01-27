A Docker container for the Phoenix framework
============================================

![Phoenix Logo](https://raw.githubusercontent.com/phoenixframework/phoenix/master/priv/static/phoenix.png)

A minimal container for development of Phoenix applications. It includes the latest versions of the following languages and frameworks:

 - Erlang
 - Elixir
 - Phoenix
 - NodeJS

Usage
-----

#### Create a new Phoenix app

    docker run -it --rm -v "$PWD":/app -w /app ruphin/phoenix mix phoenix.new .

#### Open a shell

    docker run -it --rm -v "$PWD":/app -w /app ruphin/phoenix bash

#### Run a server

    docker run -it --rm -v "$PWD":/app -w /app ruphin/phoenix