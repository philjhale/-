# Node, Typescript and Jest template

A template with Typescript, Jest, ESLint and Prettier pre-configured.

```
# Typescript
npm install typescript --save-dev
npm install @types/node --save-dev
npx tsc --init --rootDir src --outDir lib --esModuleInterop --resolveJsonModule --lib es6  --module commonjs

# Jest
npm install jest @types/jest ts-jest typescript --save-dev

# ESLint
npm i eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin --save-dev

# Prettier
npm install prettier eslint-config-prettier eslint-plugin-prettier --save-dev
```
