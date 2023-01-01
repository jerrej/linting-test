# Install & Configure ESLint & Prettier

## ESLint

### Initialize project

```
npm init --yes
```

### Install ESLint

```
npm install eslint --save-dev
```

### Initialize ESLint

```
./node_modules/.bin/eslint --init
```

or

```
npm init @eslint/config
```

Answer prompts as needed

Config file = .eslintrc.json

```
"rules" : {
    "no-console": "off"
}
```

## Prettier

### Install Prettier

```
npm install --save-dev --save-exact prettier
```

### Create config file

```
echo {}> .prettierrc.json
```

Further configuration in VSCode

## eslint-config-prettier

### Installation

```
npm install --save-dev eslint-config-prettier
```

### Add rule to eslint extends parameter

```
{
  "extends": [
    "some-other-config-you-use",
    "prettier"
  ]
}
```
