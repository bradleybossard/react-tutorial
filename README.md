# React Tutorial

My Docker command - mounts the current source code to /src and exposes the server on port 9003

docker run -it --rm -v $PWD:/src -p 9003:3000 --name react-tutorial bradleybossard/docker-node-devbox

This is the React comment box example from [the React tutorial](http://facebook.github.io/react/docs/tutorial.html).

## React Links
* [Introducing React Naive](https://www.youtube.com/watch?v=KVZ-P-ZI6W4&list=PLb0IAmt7-GS1cbw4qonlQztYV1TAW0sCr&index=1)
* [Introduction to React Javascript Library](http://developer.telerik.com/featured/introduction-to-the-react-javascript-framework/)
* [React Style Guide](https://github.com/Khan/style-guides/blob/master/style/react.md)
* [Egghead.io React Fundamentals](https://egghead.io/lessons/react-hello-world-first-component)
* [Facebook React Tutorial](https://facebook.github.io/react/docs/tutorial.html)

## Flux Links

[Flux](https://facebook.github.io/flux/docs/overview.html#content)


## To use

There are several simple server implementations included. They all serve static files from `public/` and handle requests to `/api/comments` to fetch or add data. Start a server with one of the following:

### Node

```sh
npm install
node server.js
```

### Python

```sh
pip install -r requirements.txt
python server.py
```

### Haskell

```sh
cabal sandbox init
cabal install --only-dependencies
ghc Server.hs
./Server
```

### Ruby
```sh
ruby server.rb
```

### PHP
```sh
php server.php
```

### Go
```sh
go run server.go
```

### Lua

```sh
go get github.com/xyproto/algernon
# or brew install algernon
algernon server.lua
```

### Perl

```sh
cpan Mojolicious
perl server.pl
```

And visit <http://localhost:3000/>. Try opening multiple tabs!

## Changing the port

You can change the port number by setting the `$PORT` environment variable before invoking any of the scripts above, e.g.,

```sh
PORT=3001 node server.js
```
