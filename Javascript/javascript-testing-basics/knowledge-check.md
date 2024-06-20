# Javascript Testing Basics

1. What are the benefits of TDD?

It forces the developer to give more thought into the code, which results in 
less buggy, more maintainable code in the long run. It also helps the 
developer be more confident in their code, knowing that it passes the tests
they wrote for it.

2. What are some common jest matchers?

- `toBe` checks for exact equality
- `toEqual` checks the value of the object, and recursively checks every field in an object or array
- `not` checks for the opposite
- `toBeNull` checks for null
- `toBeDefined` checks for not undefined
- `toBeUndefined` checks for undefined
- `toBeTruthy` checks for everything that evaluates to true in an `if` statements
- `toBeFalsy` checks for everything that evaluates to false in an `if` statements
- `toBeGreaterThan` is like it sounds
- `toBeGreaterThanOrEqual` is like it sounds
- `toBeLessThan` is like it sounds
- `toBeLessThanOrEqual` is like it sounds
- `toBeCloseTo` is for decimals rather than `toEqual` because it works with rounding errors
- `toMatch` checks for string matching
- `toContain` checks if an array contains something
- `toThrow` checks to see if an exception is thrown