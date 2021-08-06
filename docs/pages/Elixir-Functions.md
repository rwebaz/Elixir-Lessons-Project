---
title: Elixir Functions
layout: default
excerpt: Place the introducing line of text ie.) the 'tagline' here ...
hint: Place the intro paragraph ie.) the 'hypothesis' here ...
repo: Elixir-Lessons-Project
ver_date: 08-05-21
navigation_weight: 8
categories: template
---
{% include toc.md %}

## First Subtitle

> **Hint**. {{ page.hint }}

More to come ...

## Anonymous Functions

### Assigning (10) to X

**Rule**. Use `dot notation` to call an anonymous function, as follows:

```elixer
iex> anon.(10)
```

Yields ...

```elixir
iex> 11
```

## Anonymous or Lambda Functions in Elixir

### How to Create an Anonymous Function aka a Lambda function in Elixir

From the Elixir `inter-active` or `iex` shell`, type the following command:

```javascript
iex> anon = fn(x) -> × + 1 end
```

;where `anon` is the immutable name given the immutable variable or `const` that references the  `anonymous function` using the `fn` keyword to designate a `function` with a single argument of `x` and the anonymous single-bar `fat arrow` that points to the work that must be performed anonymously, a simple equation of the given argument `x` plus the numeral `1` followed by an `end` command to terminate the process and display the result.

### Named Functions

**Rule**. Use `question mark notation` to call a `named function` if the desired result is a `boolean` true or false only, as follows:

```elixer
iex> def namedFunc?(y) do
```

Returns ...

 ```elixer
iex> TopMod.namedFunc?(y)
```

**Note**. Use the command `defp` when defining and restricting a function to the scope of its module only

## Lambda (Anonymous) Functions in Elixir

From the Elixir `inter-active` or `iex` shell`, type the following command:

```javascript
iex> anon = fn(x) -> × + 1 end
```

## Named Functions (two)

Whereas, `Named` functions are created inside any module.

## Modules

A module is a collection of One (1) or more `relatable` functions.

### Defmodule Macro

To assign a `name` to a module, use the `defmodule` construct to create a module, as follows:

```elixir
defmodule TopMod do
```

### Named Functions (dupe)

**Rule**. Use `question mark notation` to call a `named function` if the desired result is a `boolean` true or false only, as follows:

```elixer
iex> def namedFunc?(y) do
```

Returns ...

 ```elixer
iex> TopMod.namedFunc?(y)
```

**Note**. Use the command `defp` when defining and restricting a function to the scope of its module only

## Source Code

**Note**. Source code in Elixir can be executed from a file established in the `src` subdirectory of your app.

### File Name

Set the `file name` to the same name as its `parent` module with either one of two extensions ... `.ex` or `.exs`

Then, copy the contents of your `module` into your new `ModuleName.ex`.

**Note**. The type of `Elixir source code` file does differ between `.ex` and `.exs`.

### How to Create an Anonymous Function aka a Lambda function in Elixir (dupe)

;where `anon` is the immutable name given the immutable variable or `const` that references the  `anonymous function` using the `fn` keyword to designate a `function` with a single argument of `x` and the anonymous single-bar `fat arrow` that points to the work that must be performed anonymously, a simple equation of the given argument `x` plus the numeral `1` followed by an `end` command to terminate the process and display the result

## Calling Functions

The format or protocol to `call` a function in Elixir is, as follows:

```elixir
Module Name.Function Name(Argument)
```

**Note**. Try to shy away from calling functions on objects and data and instead get used to calling functions with the module name, as follows:

For example,

```elixir
greeting = "Hello There"
String.upcase(greeting)
```
;where `greeting` is the name of a default immutable variable assigned with the string "Hello There"

;where the built-in module `String` can be chained via `dot notation` to expose one or more `named functions` ie.) `upcase` to be operated upon with the argument() enclosing the parameter `greeting`, as follows:

```elixer
 `(greeting)`
```

**Note**. Recall the parameter `greeting` is the name of an immutable variable that points to the contents of `greeting` ie.) "Hello There".

## Calling Functions (dupe)

The format or protocol to `call` a function in Elixir is, as follows:

```elixir
Module Name.Function Name(Argument)
```

**Note**. Try to shy away from calling functions on objects and data and instead get used to calling functions with the module name, as follows:

For example,

```elixir
greeting = "Hello There"
String.upcase(greeting)
```

;where `greeting` is the name of a default immutable variable assigned with the string "Hello There"

;where the built-in module `String` can be chained via `dot notation` to expose one or more `named functions` ie.) `upcase` to be operated upon with the argument() enclosing the parameter `greeting`, as follows:

```elixer
`(greeting)`
```

**Note**. Recall the parameter `greeting` is the name of an immutable variable that points to the contents of `greeting` ie.) "Hello There".

## Jekyll Server

**Note**. Detailed instructions on how to view this file locally using a Jekyll server are included in the accompanying `Gemfile` for the project.

In short, type the following command statement from a Terminal window when set to the `docs` subdirectory.

```jekyll
jekyll serve --watch --baseurl "" -o
```

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Blank Author [[1](#BLANKAUTHOR){:.red}].

1. {:#BLANKAUTHOR}[A Narrative of Psychology by Blank Author, Jan #1999](http://cowles.yale.edu/sites/default/files/files/pub/d20/d2069.pdf){:target="_blank"}

***

{% include patreon-link.md %}
