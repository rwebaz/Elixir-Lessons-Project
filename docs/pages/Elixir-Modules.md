---
title: Elixir Modules
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


## Modules

A module is a collection of One (1) or more `relatable` functions.

### Defmod

To assign a `name` to a module, use the `defmodule` construct to create a module, as follows:

```elixir
defmodule TopMod do
```


## The Do End Statement

When constructing a `function` in Elixir ...

You may use the basic `Elixiritive-function` template, as follows:

```elixir
do
# This is the body of an Elixir function
end
```

**Note**. Elixir functions can be placed in an (.exs) file and executed sequentially via the Terminal prompt by simply "calling" the name of the page, as follows:

```elixir
elixir page_name.exs
```

Returns,

```elixir
"Hello Elixirites!"
```

## Modules

Modules in Elixir can be used to segregate the one or many functions of your program.

By placing "like" functions in their own `namespace` or `module` within your program, the readability of your code is enhanced. 

### Macro Defmodule

In Elixir, a `namespace` that invokes the macro `defmodule` is called a `module` of one or more functions and can be created using the following syntax:

```elixir
defmodule name do
# Place your functions inside this `do - end` statement to create a module
end
```

;where the variable `name` identifies the module explicitly

and,

;where the variable `name` can include one or more `underscore`, as follows:

```elixir
defmodule name_your_module do
# Place your functions inside this `do - end` statement to create a module
end
```

## Scope

**Note**. Variable names given to modules cannot be invoked from outside the module. 

In other words, entire modules full of functions cannot be "called" from outside the module like a single function can be called in Elixir.