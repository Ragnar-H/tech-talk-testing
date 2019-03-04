# Material

Testing pyramid https://martinfowler.com/articles/practical-test-pyramid.html

Types, what's out there?

Unit testing, why do we write them? Helps with implementing, helps with documenting, and protects patches.
Jest, mocha, jasmine. -- Coverage report

Integration testing, in react world this can mean rendering a component to the screen with https://github.com/kentcdodds/react-testing-library

e2e testing. Appium, Detox, Cypress.

Caveats: Testing implementation details. Be aware of chasing 100% test coverage. Snapshot tests give a good coverage, but are they just noise?
