# Best configuration for react project using eslint, prettier and husky

### To see eslint config search for `eslintrc.json` file

### To see prettier config search for `.prettierrc` file

### To see typescript config search for `tsconfig.json` file

### To see husky config search for `.husky/pre-commit` file

#### Dependencies to install

```
    "@typescript-eslint/eslint-plugin": "^5.44.0",
    "@typescript-eslint/parser": "^5.44.0",
    "eslint": "^8.28.0",
    "eslint-config-airbnb": "^19.0.4",
    "eslint-config-airbnb-typescript": "^17.0.0",
    "eslint-config-prettier": "8.5.0",
    "eslint-plugin-import": "^2.26.0",
    "eslint-plugin-jsx-a11y": "6.6.1",
    "eslint-plugin-prettier": "4.2.1",
    "eslint-plugin-react": "^7.31.11",
    "eslint-plugin-react-hooks": "4.6.0",
    "prettier": "2.8.0"
    "husky": "^8.0.0"
```

#### Manual Installation

```
npm i -D -E @typescript-eslint/eslint-plugin @typescript-eslint/parser eslint eslint-config-airbnb eslint-config-airbnb-typescript eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-prettier eslint-plugin-react eslint-plugin-react-hooks prettier
```

```
npx husky-init && npm install
```

#### If you want have all those dependencies automatically run

```
npm init @eslint/config

yarn eslint --init
```

! Important if you init eslint in this way you should will install this dependencies manually:

```
    "eslint-config-airbnb": "^19.0.4",
    "eslint-config-airbnb-typescript": "^17.0.0",
    "eslint-config-prettier": "8.5.0",
    "eslint-plugin-import": "^2.26.0",
    "eslint-plugin-jsx-a11y": "6.6.1",
    "eslint-plugin-prettier": "4.2.1",
    "eslint-plugin-react-hooks": "4.6.0",
    "prettier": "2.8.0"
```
