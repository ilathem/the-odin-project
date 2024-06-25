# More Testing Knowledge Check

1. What is tightly coupled code?

Code in which modules are very dependent on each other to fulfill a purpose, such
that a change in one module affects one or more other modules.

2. What are the two requirements for a function to be pure?

The same arguments will always produce the same result, and it does not produce any
observable side effects (network requests, i/o, data mutation)

3. What are side effects and why is it important to identify them when testing
   a function?

Network requests, input/output, and data mutation. They should not be included in
testing functions, only logic should be tested.

4. What should you try before testing tightly coupled code?

To decouple the code be making each function pure.

5. How can you test code that can't be decoupled.

Through integration testing and mocking.

6. What is mocking?

Writing a fake function that imitates something you depend on in your function that
you're testing, like a network call.

7. How would you use a mock function?

To replicate behavior that is expensive or a piece of functionality that you can't
remove from the function you are testing, like a network call or i/o.

8. How should you test incoming query messages?

Assert what they send back.

9. Why should you not test implementation?

Implementation may change, but the interface will not.

10. Should you test private methods?

No, they are not seen by the outside and testing them would violate black
box testing.

11. Why should you not test outgoing messages with no side effects?

The message might as well be invisible to the rest of the app and the test is
a waste of time.
