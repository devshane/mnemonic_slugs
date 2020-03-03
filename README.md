# Mnemonic Slugs

Mnemonic Slugs is an Elixir library that generates easy to remember slugs. It 
uses a slightly enhanced word list curated by Oren Tirosh as part of his 
mnemonic encoding project.

A fork of the original project can be found [here](https://github.com/devshane/mnemonicode).

## Installation

Add mnemonic_slugs to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [{:mnemonic_slugs, "~> 0.0.3"}]
end
```

and update your dependencies with `mix deps.get`.

## Usage

You can generate slugs two ways:

```
  iex> MnemonicSlugs.generate_slug
  "aurora-bermuda"

  iex> MnemonicSlugs.generate_slug(10)
  "karate-textile-jungle-patrol-veteran-clone-nerve-stone-soviet-sting"
```

[Full Documentation](https://hexdocs.pm/mnemonic_slugs/MnemonicSlugs.html) is at HexDocs.
