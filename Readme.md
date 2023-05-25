# Conway's Game of Life <sup>[[1]]</sup>

## About

- This project is react version of Game of Life, which does not use canvas (although it's more performant).
- Here are [js-wasm](https://github.com/zkindest/rust-wa-game-of-life), [js-only](https://github.com/zkindest/js-game-of-life) versions which use canvas to render.

## How to run code?

```sh
yarn run dev # dev
yarn run build
yarn run preview
```

## Tech stack

1. react 18
2. vite as build tool
   1. css modules (for component scoped styles)
3. typescript

[1]: https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life "Conway's Game of Life"
