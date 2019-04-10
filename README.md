# ts4js
>leverage TypeScript compiler for writing plain old JavaScript

## :bulb: The idea:

I like JavaScript. I like the fact that is dynamic. I want to write JavaScript,
but we all know that sometimes an helping hand while writing our code could
simplify our life. **So, here a tsconfig that let's you write JS, while TS
compiler prevents you from introduce annoying bugs**

### The rules:

| rule | value | meaning |
|----|----|----|
| allowJs | true | Allow JavaScript files to be compiled |
| checkJs | true | support type-checking and reporting errors in .js files |
| noFallthroughCasesInSwitch | true | helpful if you never want to forget a break statement between cases in a switch block |
| noImplicitAny | true | need to explicitly set type to any |
| noImplicitReturns | true | Report error when not all code paths in function return a value |
| noImplicitThis | true | TypeScript will issue an error when this is used without an explicit (or inferred) type |
| noUnusedLocals | true | Report errors on unused locals |
| noUnusedParameters | true | Report errors on unused parameters |
| strictBindCallApply | true | Enable stricter checking of of the bind, call, and apply methods on functions |

#### Documentation:

Please check the official TypeScript documentation for more info:
* [migrating from JavaScript to TypeScript](https://www.typescriptlang.org/docs/handbook/migrating-from-javascript.html)
* [TypeScript compiler options](https://www.typescriptlang.org/docs/handbook/compiler-options.html)
