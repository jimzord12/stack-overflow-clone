# Setting Up

Files that have been modified after `pnpm create next-app` was run using all the default options.

- Check `.eslint.json`
- Check `.vscode -> setting.json`

There are 3 eslint-plugins that need to be installed:

1. `eslint-config-standard` -> enforces best practises for JS
2. `eslint-plugin-tailwindcss` -> formats the order tailwindcss classes
3. `eslint-config-prettier` -> removes all ESLint rules that could conflict with Prettier

If you do not have Prettier installed globally, install it:

`pnpm install prettier`

Additionally, **3 VS Code extentios** are required:

1. ESLint
2. Prettier - Code formatter
3. Prettier ESLint
