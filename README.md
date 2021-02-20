# Identicon

Identicon is a service for generating Identity Icons based on a string
Generated Images are saved to the User Computer on the project folder

## Table of Contents

- [Identicon](#identicon)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Demo](#demo)

## Installation

Have [Elixir](https://elixir-lang.org/install.html) Installed
Clone this project:

```sh
git clone https://github.com/EnzoBtv/identicon-gen.git
```

## Usage

In project folder run:
```sh
mix deps.get # Get dependencies used for this project
iex -S mix # Opens a virtual elixir environment
```

With IEX open, run:
```elixir
Identicon.main("some_string_to_generate_identicon")
```

And then an image will be created in your project folder with the specified name

## Demo
[![GRAPHIC1](https://imgur.com/wVSSIuR)]()