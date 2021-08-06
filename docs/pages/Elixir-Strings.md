---
title: Elixir Strings
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

## Elixir Strings

From the `iex` prompt, type the command `h` followed immediately by the name of the `module` associated with the concept of UTF-8 binaries in Elixir, as follows:

```elixir
iex> h(String)
```

;where the module name of `String` in parenthesis returns the resident `help` library or `man` or `manual` pages for the module `String`

### Concatenation

The merging of "two-or-more-strings" in Elixir is performed by the `++` or `double-plus` sign, as follows:

```elixir
iex> x = "Hello"
x
"Hello"
```

And, 

```elixir
iex> y = "there"
x
"there"
```

And,

```elixir
iex> z = "!"
x
"there"
```

```elixir
iex> x `++` y `++` z = :a
```

;where the formula "×" or `the string of x` concatenated with "y" or `the string of y`  concatenated with "z" or `the string of z` is assigned to the `Atom-variable` of the same name `:a`

Returns,

```elixir
iex>
```

## Interpolation

**Note**. `Strings` aka `UTF-8 binaries` in Elixir do support the process of `interpolation` using the `#{...}` syntax

1.) Invoke the `interactive Elixir-shell` from a global Terminal window with the `iex` command ...

```elixir
iex>
```

;where the `iex` command starts an instance of Elixer

2.) Assign a `string` to a variable

```elixer
iex> name = "joe"
```

;where the string of "joe" is assigned to the variable `name`

3.) Insert the `value` of the variable `name` within any string using the given `#{...}` format, as follows:

```elixer
iex> "hello #{name}"
```

Returns,

```elixir
"hello joe"
```

### Strings as Keys in Elixir

Use the `%` sign plus a set of curly braces `{ ... }` to create a `data map` or `dictionary` or simply a  `map` in Elixir as follows:

```elixir
iex> x = %{ "a" => 3, "b" => 4 }
```

**Note**. The `fat arrow` designates a `key => value` pair within a `map`.

;where the `name` of the map is assigned to the variable placeholder `x`

**Note**. `Dictionaries` in `Python3` are called `Maps` in Elixir.

```elixir
 => 3, ":b" => 4 }
```

;where

Or,

iex> x = %{:a 3, :b 4}

Returns,

iex> unknown

 Or,

x[:a]

Returns,

3

;where `colon a` is an `atom` in the Elixir programming language ie.) the immutable variable `a` of the same name or `:a`

**Note**. One of the benefits of using `atoms` as your immutable variable of choice is the automatic naming convention for `atoms`.

For example, `colon a` or simply `:a` is the `atom` or immutable variable named `a`

## Strings in Elixir

From the `iex` prompt, type the command `h` followed immediately by the name of the `module` associated with the concept of UTF-8 binaries in Elixir, as follows:

```elixir
iex> h(String)
```

;where the module name of `String` in parenthesis returns the resident `help` library or `man` or `manual` pages for the module `String`


### String-keys

```elixir
iex> x = %{ "a" => 3, "b" => 4 }
```

;where 

Or,

iex> ×["a"]

Returns,

iex> "a"

### String Concatenation

The merging of "two-or-more-strings" in Elixir is performed by the `++` or `double-plus` sign, as follows:

```elixir
iex> x = "Hello"
x
"Hello"
```

And, 

```elixir
iex> y = "there"
x
"there"
```

And,

```elixir
iex> z = "!"
x
"there"
```

```elixir
iex> x `++` y `++` z = :a

;where the formula "×" or `the string of x` concatenated with "y" or `the string of y`  concatenated with "z" or `the string of z` is assigned to the `Atom-variable` of the same name `:a`

Returns,

iex> 

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
