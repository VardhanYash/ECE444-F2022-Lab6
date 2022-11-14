# ECE444-F2022-Lab6

Unit Test in Education Pathways Project: https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-15-runtime-terror/blob/epic-5-2-compare-page/Education_Pathways/tests/test_app.py#L69-L75


Pros of TDD:
One of the pros of TDD is allowing the code to be more modular since the tests are written first to test a particular part of the system.  It helps you practice good modular design. With this modular design it also means that the code is able to maintain it's architecture much better. It also allows for much better code maintainability due to issues being shown much sooner and the debugging process being simplified as a result of the tests that were written. Collaboration with other team members is also much easier since modifying someone else's code can be done with confidence because the tests will inform if a change has caused the system to behave in an unexpected manner.

Cons of TDD:
A con of TDD may be that the tests are not written to be deterministic and rely on external dependencies and may not accurately represent a real usage scenario. The tests may also be difficult to write for a situation. Doing TDD also initially slows down development since a test has to be written and then actual code to pass that test has to be written as well, requiring the developer to write a lot more code. If you are given legacy code to work with it is a lot harder to implement as well, given that the legacy code wasn't using TDD already. You must also continously maintain the tests as more and more changes are added to the system which requires additional effort from the developers. Not maintaining tests can lead the whole system to degrade quickly. 
