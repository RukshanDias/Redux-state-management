# Redux state management

[1. Redux vs NgRx](https://github.com/RukshanDias/Redux-state-management#redux-vs-ngrx)
[2. Setup Redux dev-tools](https://github.com/RukshanDias/Redux-state-management#setup-redux-dev-tools)

## Redux vs NgRx
- Redux - mainly developed for react.
- NgRx - uses Redux principles with rxjs as the undeline library.
- Both shares similar patterns.

## setup Redux dev-tools
- chrome extension to view app state in a visual manner.
- 1st install npm package, 2nd import & declare.
```
npm i @ngrx/store-devtools --save

import { StoreDevtoolsModule } from '@ngrx/store-devtools';
StoreDevtoolsModule.instrument({
      maxAge: 10, // number of states to show
    }),
```