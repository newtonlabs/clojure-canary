# hello-world

A Clojure library designed to show how nginx-clojure does their bits

## Usage

Used with [clojure-nginx-stack](https://github.com/newtonlabs/clojure-nginx-stack)

Does not specifiy handler, to repl-ify

```
(use 'ring.adapter.jetty)
(use 'hello-world.core)
(run-jetty handler {:port 8080})
```

