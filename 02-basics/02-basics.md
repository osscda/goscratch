# Go Basics

This is the section where you learn how to do "Hello World"!

Well, not really. That's boring.. Let's do something a liiitle more interesting. Let's build a simple counter. It will be a command line (CLI) application that just counts from zero and up forever.

You can find the code in [`main.go`](./main.go), but before you look there, check out this skeleton below:

```go
package main

func main() {
    // do things here!
}
```

Let's break it down line by line.

## Newlines

First, _empty_ newlines generally don't matter in Go. You can write all your code line by line with no whitespace, but it certainly helps readability to add blank lines!

## `package main`

Every Go file needs to have a package name at the top. Multiple files with the same `package` name in the same directory make up a ... wait for it ... "package".

Any Go file can get access to everything else in a package. That means that you can use functions, variables, and more that might not be in a given Go file.

Finally, every go program needs to have at least one file, and it has to be `package main`.

## `func main()`

This is a `func`tion (see what I did there?) called `main`. Semantically, a function is very similar to what you'd expect from other languages.

Here's how the `func main()` breaks down:

- All functions start with `func ` (notice the trailing space)
- The `main` is the name of the function
- The `()` is the argument list for the function. `main` never takes any arguments though. Other functions can!
- The `{` starts the body of the function, where you write the logic

Finally, some functions can return one or more values as well. Those would be provided after the `()` but before the `{`. `main` never returns arguments though.
