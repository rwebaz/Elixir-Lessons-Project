---
title: Elixir Maps
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

### Elixir Maps

From the `iex` prompt or `iex>` ...

Type the command `h` followed immediately by the name of the `Module` associated with the concept of `dictionaries` or `Maps` in Elixir, as follows:

```elixir
iex> h(Map)
```

;where the Module name of `Map` in parenthesis returns the resident `help` library or `man` or `manual` pages for the module `Map`

#### Map functions

```elixer
iex> Map.get(x, :a)
```

Returns,

```elixir
iex> 3
```

## Elixir Maps

### Strings as Keys in Elixir

Use the `%` sign plus a set of curly braces `{ ... }` to create a `data map` or `dictionary` or simply a  `map` in Elixir as follows:

```elixir
iex> x = %{ "a" => 3, "b" => 4 }
```

**Note**. The `fat arrow` designates a `key => value` pair within a `map`.

;where the `name` of the map is assigned to the variable placeholder `x`

**Note**. `Dictionaries` in `Python3` are called `Maps` in Elixir.

## Maps in Elixir

From the `iex` prompt or `iex>` ...

Type the command `h` followed immediately by the name of the `Module` associated with the concept of `dictionaries` or `Maps` in Elixir, as follows:

```elixir
iex> h(Map)
```

;where the Module name of `Map` in parenthesis returns the resident `help` library or `man` or `manual` pages for the module `Map`

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
