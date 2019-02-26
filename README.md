# TACHYONS EXTENDED

Extended styles for tachyons.

## Features

* Added `xl` breakpoint
* Added `a` modifiers to margin for `auto`

## Getting started

Import along side of tachyons.

### Local Setup

Clone the repo from github and install dependencies through npm.

```
git clone https://github.com/tachyons-css/tachyons.git
cd tachyons
yarn install
```

#### Dev

If you want to just use everything in tachyons/src as a jumping off point and
edit all the code yourself, you can compile all of your wonderful changes by
running

```yarn run start```

This will output both minified and unminified versions of the css to the css directory and watch the src directory for changes.
It's aliased to the command:

```yarn run build:watch```

If you'd like to just build the css once without watching the src directory run

```yarn run build```

If you want to check that a class hasn't been redefined or 'mutated' there is a linter to check that all of the classes have only been defined once. This can be useful if you are using another library or have written some of your own css and want to make sure there are no naming collisions. To do this run the command

```yarn run mutations```

## Help

If you have a question or need help feel free to [open an issue here](https://github.com/sky-foundry/tachyons-extended/issues/new).
