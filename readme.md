
### Run the project locally

```
yarn start:dev
```

### Build the project

```
yarn buil
```
// Setup tsconfig

npx tsc --init --rootDir src --outDir dist --resolveJsonModule --lib es6 --module commonjs --allowJs false --noImplicitAny true --target esnext --esModuleInterop false
```

tsconfig test

```
{
  "compilerOptions": {
    "module": "NodeNext",
    "moduleResolution": "NodeNext",
    "target": "ES2020",
    "sourceMap": true,
    "outDir": "dist",
  },
  "include": ["src/**/*"]
}
```

https://the-guild.dev/graphql/codegen