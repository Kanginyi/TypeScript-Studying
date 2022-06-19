## What is TypeScript?

- TypeScript is a syntactic superset of JavaScript, which adds **static typing**.
- Allows developers to use TS syntax to add **types**.

## Why should we use TypeScript?

- JavaScript is a loosely typed language
- TypeScript specifies the *types* of data being passed around inside code and tells you when the *types* don't match

>TypeScript uses *compile time type checking*.
>This means it checks if the types match **before** running code, not **during** run time.

---

## Installing & Configuring the Compiler

-TypeScript is transpiled into JS using a compiler. This mean it can be run wherever JS runs.

Within an npm project, run:
```
npm install typescript --save-dev
```

We can configure this compiler using a **tsconfig.json** file, which can be created using:
```
npx tsc --init
```

We can add or edit options inside of the **tsconfig.json** file to manipulate how we want TypeScript to work for us.