# Angular NgRx Store & Effects Starter

A minimal Angular scaffold with NgRx (Store, Effects, Entity, Store DevTools) wired into the app module as a starting point for building out feature state, actions, reducers, and effects.

## What's inside

- `RootStoreModule` — an empty root module intended to host feature state modules as the app grows; currently declares no reducers or effects.
- `State` — an empty root state interface, ready to be extended per feature.
- Default Angular CLI app shell (`AppComponent`, routing module) with the standard generated landing page.

Note: the NgRx packages are installed and the root store module is registered in `AppModule`, but no feature state, actions, reducers, or effects are implemented yet — this is a clean starting point rather than a working state-management demo.

## Tech stack

- Angular (TypeScript)
- NgRx Store, Effects, Entity, Store DevTools
- RxJS
- Karma / Jasmine for unit tests
- Protractor for end-to-end tests

## Quickstart

```bash
yarn install
yarn start
```

Navigate to `http://localhost:4200/`.

Other scripts:

```bash
yarn build   # production build to dist/
yarn test    # unit tests via Karma
yarn e2e     # end-to-end tests via Protractor
yarn lint    # lint via ng lint
```

## Project structure

```
src/app/
  app.module.ts              # registers RootStoreModule
  root-store/
    root-store.module.ts     # empty root store module (extend with feature modules)
    root-state.ts            # empty root State interface
```
