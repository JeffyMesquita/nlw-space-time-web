## Start NextJs Project

```bash
npx create-next-app@latest `app-name` --use-npm
```

#### 1. Install rocketseat Eslint

```bash
npm i @rocketseat/eslint-config -D
```

#### 2. Add in .eslintrc.js

```js
"extends": [
  "next/core-web-vitals",
  "@rocketseat/eslint-config/react"
]
```

#### 3. Install Prettier

```bash
 npm i prettier-plugin-tailwindcss -D
```

#### 4. Create prettier.config.js

```js
module.exports = {
  plugins: [require("prettier-plugin-tailwindcss")],
};
```

#### 5. Install Lucide for Icons

```bash
npm i lucide-react
```
