# gobstopper

A highly opinionated golang http stack.

You can use this project in two ways as a starter template or import the core packages in your existing project.

### `[mux](http://www.gorillatoolkit.org/pkg/mux)` - Router

> The name mux stands for "HTTP request multiplexer".
> Like the standard http.ServeMux, mux.Router matches incoming
> requests against a list of registered routes and calls a handler
> for the route that matches the URL or other conditions.

### `[negroni](https://github.com/codegangsta/negroni)` - Middleware Manager

> Negroni is an idiomatic approach to web middleware in Go.
> It is tiny, non-intrusive, and encourages use of net/http Handlers.

### `[sqlx](https://github.com/jmoiron/sqlx)` - Database (optional)

> sqlx is a library which provides a set of extensions on go's standard database/sql library.
> The sqlx versions of sql.DB, sql.TX, sql.Stmt, et al.
> all leave the underlying interfaces untouched, so that
> their interfaces are a superset on the standard ones.


## Core Packages

Gobstopper consists of two packages:

### `database` - [Go docs]()

To use this package...

```golang
import github.com/seedboxtech/gobstopper/db
```

To use this package...

### `service` - [Go docs]()

```golang
import github.com/seedboxtech/gobstopper/service
```