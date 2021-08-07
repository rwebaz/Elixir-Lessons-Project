---
title: Erlang v Elixir
layout: default
excerpt: The Elixir `Functional Programming Language` or (FNL) is built on top of the Erlang virtual machine ...
hint: There are spots in the code where the two languages, Elixir and Erlang ... differ.
repo: Elixir-Lessons-Project
ver_date: 08-07-21
navigation_weight: 8
categories: page
---
{% include toc.md %}

## Scope

> **Hint**. {{ page.hint }}

As such, `Elixir` will incorporate features from the underlying `Erlang` computer language.

One of those areas of overlap and segregation is the `Concept of Delimiters`.

## Delimiters

### How to Terminate a line of code in Elixir

There are Two (2) ways to Terminate a line of code in Elixir, as follows:

From the Terminal app ...

```elixir
x + y;
```

;where the `semi-colon` terminates an expression

And,

```elixir
x + y
```

;where a simple `line-break` terminates the expression `x + y`

**Note.** In Erlang the comma or `,` is used to separate expressions in a single line of code, as follows:

From the Terminal app ...

```erlang
x + y, z - 7.
```

**Note**. Also notice the period or `.` at the end of the above `Erlang` line of code.

The period or `.` terminates a line of code in the `Erlang` language, but not so conventionally in the `Elixir` language.

## Jekyll Server

**Note**. Detailed instructions on how to view this `GitHub Pages` file locally using a Jekyll server are included in the accompanying `Gemfile` for the project.

In short, type the following command statement from a Terminal window when set to the `docs` subdirectory.

```jekyll
jekyll serve --watch --baseurl "" -o
```

Your browser will pop up to display the page. Otherwise, an error message as to why not will appear.

## Credits

More to come ...

***

**Note**. The above synopsis was derived from an article written by `Elixir-Lang dot org` [[1](#ELIXIRLANG){:.red}].

1. {:#ELIXIRLANG}[Elixir Language Crash Course](https://elixir-lang.org/crash-course.html){:target="_blank"}

***

{% include patreon-link.md %}
