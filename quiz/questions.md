---
1. A Dummy object is typically used when:

    A) one needs to simulate the behaviour of an external system
    B) a method requires a parameter, and its actual value is uninfluent
    C) there is a need to verify how many times the parameter is handled
    D) we want to replace a dependency with a lightweight implementation

----
2. The purpose of a Stub double is:
    
    A) to verify method calls
    B) to provide business-relevant responses
    C) to replace an entire class
    D) to simulate the behaviour of an external system
    
----
3. What is the primary role of a Mock object in unit testing?

    A) to replace an internal dependency and verify its usage
    B) to provide hardcoded responses without verifying their usage
    C) to simulate the behaviour of external dependencies
    D) to track method calls on a real object

----
4. What is the difference between Mock and Patch doubles?

    A) they serve different
    B) there is no difference
    C) Mocks use substitution, Patches override dependencies
    D) Mocks act at run time, Patches at compile time

----
5. What is the primary use of a Spy in unit testing?

    A) to completely replace a class with a test-friendly alternative
    B) to act as a simple placeholder with no behavior
    C) to track interactions with a real object while partially overriding behavior
    D) to modify existing dependencies at runtime

----
6. What distinguishes a Fake from other types of test doubles?

    A) It mimics real behavior of external dependencies
    B) It replaces dependencies to verify how they were interacted with
    C) It provides hardcoded responses without implementing real logic
    D) It dynamically modifies function behavior at runtime during testing
