---
title: Functional Programming
layout: default
excerpt: The `Elixir` app comes bundled with `ErLang` aka the `BEAM` virtual machine ...
hint: Object-oriented Programming (OOP) versus Functional Programming (FNP) ...
repo: Elixir-Lessons-Project
ver_date: 08-05-21
navigation_weight: 8
categories: template
---
{% include toc.md %}

## OOP v FNP

> **Hint**. {{ page.hint }}

## Erlang

Note. The `Elixir` app comes bundled with `ErLang` Functional programming app plus the `BEAM` virtual machine.

## Session Maintenance

Elixir has several ready commands at the developer's disposal.

Here are some examples of basic commands.

### How to Begin a new Elixer Session from the Terminal via REPL

The command `iex` spins up a new `Elixir Session` from the Terminal window set to your app's root folder, as follows:

```elixir
iex
```

**Note**. The `iex`command works inside a type of `Elixir-shell` called a `Read-Evaluate-Print-Loop` or (REPL).

**Note**. The above command spins-up a new `Elixer Session` that produces an `iex` prompt`, as follows:

```javascript
iex>
```

### How to Begin a new Elixer Session from the Terminal via CODE

More to come ...

### EXS vs EX

Test files generally use the `.exs` extension and are NOT compiled to disk as a set of hidden `dot beam` files.

Whereas, the `.ex` extension is used when simply working on an app

;where all app code placed inside the `module` are compiled to disk as a set of hidden `dot beam` files.

### How to Terminate your Elixer Session from the Terminal

From the Terminal window ...

;where your instance of the Elixir app is running ...

Type the following command ...

```elixir
system.halt
```

or,

Simple hit the `Control-C` combo key TWICE

```elixir
 Control-c (twice)
```

### How to Terminate Your Elixer Session

From the Terminal window ...

;where your instance of the Elixir app is running ...

Type the following command ...

```javascript
system.halt
```
 or,

```javascript
 Control-c (twice)
```

### Clear Terminal Window

**Tip**. At any time while working with Elixer's `Interactive Shell` via the Terminal simply type the command `clear` and press `enter` to wipe the `Interactive Shell` clean.


### How to Clear the Terminal window during an Elixir Session

**Tip**. At any time while working with Elixer's `Interactive Shell` or (REPL) via the Terminal simply type the command `clear` and press `enter` to wipe the `Interactive Shell` clean.

## Async Tasks

More to come ...

## BEAM Files

**Rule**. The source code file ending in the  `.ex` extension is automatically compiled to disk thus creating a set of hidden `dot beam` or files with a `.beam` extension.

Whereas, the source code file ending with the  `.exs` extension is compiled only in memory rather than compiling the file to disk as a hidden `dot beam` file.

No hidden `dot beam` files are created.

## Elixir OTP

More to come ...

## Elixer Gen Servers

More to come ...

## Immutability

**Rule**. A variable `name` can be re-assigned in Elixer.

However, the underlying value remains immutable.

For example, changing the assignment of a variable from (x) to (y) does not change the underlying value the newly assigned variable is pointing to.

### Immutability (dupe)

**Rule**. A variable `name` can be re-assigned in Elixer.

However, the underlying value remains immutable.

For example, changing the assignment of a variable from (x) to (y) does not change the underlying value the newly assigned variable is pointing to.

### Assigning (10) to x

**Rule**. Use `dot notation` to call an anonymous function, as follows:

```elixer
iex> anon.(10)
```

Yields ...

```elixir
iex> 11
```

## BEAM Files (dupe)

**Rule**. The source code file ending in the  `.ex` extension is automatically compiled to disk thus creating a set of hidden `dot beam` or files with a `.beam` extension.

### Elixir Scripts

Whereas, the source code file ending with the  `.exs` extension is compiled only in memory rather than compiling the file to disk as a hidden `dot beam` file.

No hidden `dot beam` files are created.

## Source files

### Src

Source code in Elixir can be executed from a file established in the `src` subdirectory of your app.

Set the `file name` to the same name as its `parent` module with either one of two extensions ... `.ex` or `.exs`

Then, copy the contents of your `module` into your new `ModuleName.ex`.

**Note**. The type of `Elixir source code` file does differ between `.ex` or `.exs`.

## Session Termination

### Test Files

Test files generally use the `.exs` extension and are NOT compiled to disk as a set of hidden `dot beam` files.

Whereas, the `.ex` extension is used when simply working on an app

;where all app code placed inside the `module` are compiled to disk as a set of hidden `dot beam` files.

## Lists, Tuples and Maps in Elixir

- char-lists

### Elixir Lists

More to come ...

### How to Concatenate 2-Lists

More to come ...

```elixir
iex> x = [1, 2, 3] ++ [4,5,6]
```

Returns,

```elixer
iex> [1, 2, 3, 4, 5, 6]
```

### How to Return the Head of the List

iex> hd(lst)

Returns,

iex> 1

### How to Return the Tail of the List

iex> tl(lst)

Returns,

iex> 2,3,4,5,6

## The Pin Operator

The `pin operator` or `^` or "hat" can precede the assignment of a variable to stop the `Match function`, as follows:

```elixir
iex> ^x = 22
```

Returns,

```elixir
iex> 22
```

## Jekyll Server

More to come ...

**Note**. Detailed instructions on how to view this file locally using a Jekyll server are included in the accompanying `Gemfile` for the project.

In short, type the following command statement from a Terminal window when set to the `docs` subdirectory.

```jekyll
jekyll serve --watch --baseurl "" -o
```

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by André Albuquerque [[1](#ANDREALBUQUERQUE){:.red}] and Daniel Ciaxinha [[2](#DANIELCIAXINHA){:.red}] via `@packtPub`

1. {:#ANDREALBUQUERQUE}[Mastering Elixir](https://subscription.packtpub.com/book/application_development/9781788472678/1/ch01lvl1sec14/functions-and-modules?uuid=cc36e816-6930-4834-852a-206c35a8c895){:target="_blank"}

2. {:#DANIELCIAXINHA}[Mastering Elixir](https://subscription.packtpub.com/book/application_development/9781788472678/1/ch01lvl1sec14/functions-and-modules/){:target="_blank"}

***

{% include patreon-link.md %}
