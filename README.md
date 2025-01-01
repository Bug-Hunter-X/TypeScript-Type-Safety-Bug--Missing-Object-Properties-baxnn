This repository demonstrates a common type-safety issue in TypeScript where optional properties are not handled correctly. The `printCoord` function expects an object with both `x` and `y` properties. However, if an object missing either property is passed, TypeScript's type checking won't catch it, leading to a runtime error. The solution uses optional properties and a type guard to improve the function's robustness.