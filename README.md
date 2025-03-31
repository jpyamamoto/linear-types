![Logo](image.png)

# Linear Types in Haskell

Haskell project containing the code I developed to accompany my Bachelor's thesis: "Tipos Lineales en Haskell" (Linear types in Haskell).

The project uses the GHC extension `LinearTypes` that enables the use of linear types.

For more information on the `LinearTypes` extension, make sure to check the paper by Bernardy, Boespflug, Newton, Peyton-Jones and Spiwack: _"Linear Haskell: practical linearity in a higher-order polymorphic language"_.

## Run Locally

Clone the project

```bash
  git clone https://github.com/jpyamamoto/linear-types
```

Go to the project directory

```bash
  cd linear-types
```

Update cabal dependencies

```bash
  cabal update
```

Build the project

```bash
  cabal build
```

Run an executable

```bash
  cabal run <app>
```

The following are the available apps:

- `unsafe`: Use different optimization levels to get a different result.
- `destination-arrays`: An example that uses destionation arrays to populate an array by segments.
- `polarized-arrays`: Perform mergesort on an array using a polarized flow.
- `summed-area`: Build a [summed area table](https://en.wikipedia.org/wiki/Summed-area_table) using linear matrices.

## License

Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License. See [LICENSE](LICENSE) for more information.

## Authors

- [@jpyamamoto](https://www.github.com/jpyamamoto) - [jpyamamoto.com](https://jpyamamoto.com/)
