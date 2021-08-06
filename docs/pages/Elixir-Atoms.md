---
title: Elixir Atoms
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

## Elixir Atoms

`Atoms` are a type of `Erlang constant` that hold the same name as their value.

;where the value of the `Erlang constant` or `atom` is equal to the name assigned to the `Erlang constant`

**Tip**. `Erlang constants` ie.) `Atoms` in the Elixer programming language are always pre-fixed with a leading colon `(:)`, as follows:

```elixer
:OneAtom
```

;where `OneAtom` is the `CamelCase` name of the `atom` OneAtom

## Atoms (dupe)

`Atoms` are a type of `Erlang constant` that hold the same name as their value.

;where the value of the `Erlang constant` or `atom` is equal to the name assigned to the `Erlang constant`

**Tip**. `Erlang constants` ie.) `Atoms` in the Elixer programming language are always pre-fixed with a leading colon `(:)`, as follows:

```elixer
:OneAtom
```
;where `OneAtom` is the `CamelCase` name of the `atom` OneAtom

## Elixir Atoms (dupe)

More to come ...

### Atom-keys

```elixir
iex> x = %{ ":a"
```

### Atoms as Keys in Elixir

Use the `%` sign plus a set of curly braces `{ ... }` to create a `data map` or simply a  `map` in Elixir using `strings` or `atoms` as keys, as follows:

#### String-keys

```elixir
iex> x = %{ "a" => 3, "b" => 4 }
```

;where

Or,

iex> ×["a"]

Returns,

iex> "a"

### Atomic Table

**Rule**. `Atoms` are immutable in the Elixer programming language.

`Atoms` are kept and stored by the Elixer program in their very own `atomic table`.

**Note**. Upon compilation at `runtime`, the `value` of the `Atom` is replaced by a `reference` pointing to the corresponding entry for the `Atom` within the `Atomic Table`.

### Atomic Table

**Rule**. `Atoms` are immutable in the Elixer programming language.

`Atoms` are kept and stored by the Elixer program in their very own `atomic table`.

**Note**. Upon compilation at `runtime`, the `value` of the `Atom` is replaced by a `reference` pointing to the corresponding entry for the `Atom` within the `Atomic Table`.

### Atoms as Keys in Elixir

Use the `%` sign plus a set of curly braces `{ ... }` to create a `data map` or simply a  `map` in Elixir using `strings` or `atoms` as keys, as follows:

## Sigils

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

### Atom-keys

```elixir
iex> x = %{ ":a" => 3, ":b" => 4 }
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

## Jekyll Server

**Note::. Detailed instructions on how to view this file locally using a Jekyll server are included in the accompanying `Gemfile` for the project.

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
