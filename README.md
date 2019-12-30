# Cod Microframework
Cod is a microframework written and implemented in C.
Its purpose is to provide a simple and easy-to-use api that allows anyone to make any level of website.
The goal is to not have any external dependencies other than the operating system it is running on.

## Inspiration
The inspiration behind this project is the lack of a solid microframework right now.
We have a little heavier-weight options, like AspNet, but in terms of microframeworks, the scene is quite barren.
Cod aims to fix this by providing a nice, simple, complete microframework.
The goal is to eventually provide bindings to as many languages as we can, such as Java, C#, Python, and PHP.

## Current status
Right now, we are still in extremely early development.
Things aren't expected to actually be working for a while, until we at least have implemented the base for running a server.
For that to be working, we need a Cod API, as well as an implementation of HTTP 1.1.
Sit tight, and check back in a while!

## Using
To use Cod, first you need to build it.
To do this, you must have [Meson](https://mesonbuild.com/) installed, as that is our build system.
Next, you can build the project to a `build` directory, using the following command:
```cmd
meson build
```
That will build the project into the `build` directory, where you can find the products.

The rest is a work-in-progress.
Wait for more!
