## Acceptance-Testing

### Definitions

A formal description of the behavior of a software product, generally expressed as an example or a usage scenario
[Source: Agile Alliance](https://www.agilealliance.org/glossary/acceptance/)

### The 3 Cs: Card, Conversation, Confirmation

- The Three Cs of Card, Conversation, Confirmation were suggested by Ron Jeffries in 2001.
- The most common way to specify what is required for *Confirmation* of your user stories is to create a set of acceptance tests for each user story.

### Format of a Rule/Test

> `GIVEN` > `WHEN` > `THEN` 

Example: If *user has no Internet connectivity* and *user attempts to view the updates*, then *a No Internet dialog should pop up*

| GIVEN      | WHEN          | THEN  |
|:-------------:|:-------------:|:-------------:|
| user has no Internet connectivity | user attempts to view the updates | a No Internet dialog should pop up |

### Resources

- [Specifying with examples](https://gojko.net/2008/11/04/specifying-with-examples/)
- [Behind-the-Scenes: How We’re Automating Acceptance Testing](https://deliciousbrains.com/how-were-automating-acceptance-testing/)
