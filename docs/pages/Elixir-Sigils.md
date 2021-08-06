---
title: Elixir Sigils
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


##Sigils 

**Note**. The Sigil `~w()` statement in the Elixer programming language produces a set of `key` or `seed` words or `strings`, as follows:

```elixer
iex> ~w(one two three)s
```

;where the switch of `s` suffixed to the rear or caboose of the `Sigil-statement` returns all values as `strings`, as follows:

Returns ...

```elixer
["one", "two", "three"] 
```

Or,

As `atoms` when evoking the `a` suffix to the `Sigil-statement`, as follows:

```elixer
iex> ~w(one two three)a
```

Returns ...

```elixir
[:one, :two, :three] 
```

**Note**. `Anonymous` functions are created OUTSIDE of any module in Elixer.

**Rule**. Use `dot notation` to call an anonymous function, as follows:

```elixer
iex> anon.(10)

Whereas, `Named` functions are created inside any module.
