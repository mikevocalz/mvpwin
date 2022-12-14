# Mike Portfolio App: Windowsπ΄

```sh
npx create-solito-app@latest my-solito-app
```

πΎ [View the website](https://example.solito.dev)

## π¦ About

This monorepo is a blank(ish) starter for an Expo + Next.js app.

While it's pretty barebones, it does a lot of the annoying config for you. The folder structure is opinionated, based on my long experience building for this stack.

## π¦ Included packages

- `solito` for cross-platform navigation
- `moti` for animations
- `dripsy` for theming/design (you can bring your own, too)
- Expo SDK 44
- Next.js 12
- React Navigation 6

## π Start the app

- Install dependencies: `yarn`

- Next.js local dev: `yarn web`
  - Runs `yarn next`
- Expo local dev: `yarn native`
  - Runs `expo start`

## π Add new dependencies

### Pure JS dependencies

If you're installing a JavaScript-only dependency that will be used across platforms, install it in `packages/app`:

```sh
cd packages/app
yarn add date-fns
cd ../..
yarn
```

### Native dependencies

## π About the creator

Follow Fernando Rojo on Twitter: [@FernandoTheRojo](https://twitter.com/fernandotherojo)

## π§ Why use Expo + Next.js?

See my talk about this topic at Next.js Conf 2021:

<a href="https://www.youtube.com/watch?v=0lnbdRweJtA"><img width="1332" alt="image" src="https://user-images.githubusercontent.com/13172299/157299915-b633e083-f271-48c6-a262-7b7eef765be5.png">
</a>
