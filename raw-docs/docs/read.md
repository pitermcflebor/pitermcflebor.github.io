# How to read the docs

This sounds very stupid, but lets explain how to read the docs.

At the left-side of this page you have a navigation bar where you can see
all existent classes. Inside every class you have 3 types `Common`, `Client` and `Server`.

For example:

`StateBag` has inside `Common` and inside of it you have the methods inside `StateBag`.
This means every method inside `Common` is the same on **client-side** and **server-side**.

Every method inside `Common` will be run using `:` (ex: `state:set()`), but this is explain at the
bottom of every method inside the `Examples`.