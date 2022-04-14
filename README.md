# Identicon - Elixir

Simple application that generates an identicon for a given string.

## Example

```elixir
iex> Identicon.main("elixir")
:ok
```
images/elixir.png:

![identicon: elixir](images/elixir.png)

## Installation

> Elixir installation: https://elixir-lang.org/install.html

First you will need to install the dependencies:
```bash
mix deps.get
```

Then you can start generating identicons:

```bash
iex -S mix

iex> Identicon.main("your_string_here")
```