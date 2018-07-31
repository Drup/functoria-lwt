Functoria-lwt
--------------

[Functoria](https://github.com/mirage/functoria) is a library to create DSL
manipulating such functor-based libraries. It was originally created for
[mirageOS](https://mirage.io/) (See [this blog post](https://mirage.io/blog/introducing-functoria) for more details).

functoria-lwt is a minimal example of how to build a functoria DSL to build
lwt-based applications.

## Install

```
opam pin add functoria-lwt "https://github.com/Drup/functoria-lwt.git"
```

To try out the example:

```
cd example/
functoria-lwt config
opam install --deps .
functoria-lwt build
```
