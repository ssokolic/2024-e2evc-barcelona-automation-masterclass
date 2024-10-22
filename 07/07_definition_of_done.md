Definition of Done

The definition of done is a common agreement of the team as to what has to be done to make a piece of work done. Some examples below:

Sophisticated DoD
• Story can be released
• Story is unit tested
• Story is integration tested
• Story was successfully tested on QA and marked as "Ready for Production"
• Project builds without errors
• Unit tests written and passing
• Release Notes updated
• No additional technical debt created
• Customer Acceptance Test successful
• Feature ok-ed by Product Owner
• Product Backlog updated
• FAQ for new feature updated
• User documentation updated (e.g. in app guidance is up to date)
• Technical documentation is updated

DEFINITION OF DONE (EXAMPLE)

A Definition of Done properly applies to an increment.

Environments are prepared for release

First check that no unintegrated work in progress has been left in any development or staging environment. Next, check that the continuous integration framework is verified and working, including regression tests and automated code reviews. The build engine ought to be configured to schedule a build on check-in. It may also trigger hourly or nightly builds. Also, check that all of the test data used to validate the features in the release has itself been validated.

Handover to support is complete

(Note: This may be elided in a DevOps context or where the Dev Team will follow the product through to support)

All design models and specifications, including user stories and tests, must be accepted by support personnel who will maintain the increment henceforth. Note that they must also be satisfied that they are in competent control of the supporting environment.

Review Ready

Part of the work in a Sprint includes preparing for the review. Sprint metrics ought to be available, including burn-down or burn-up charts. Any user stories which have not been completed ought to be re-estimated and returned to the Product Backlog.

Code Complete

Any and all “To Do” annotations must have been resolved, and the source code has been commented to the satisfaction of the Development Team. Source code should have been refactored to make it understandable, maintainable and better able to support future change. Note that the Red-Green-Refactor pattern found in Test Driven Development is helpful here.

Unit test cases must have been designed for all of the features in development, and allow requirements to be traced to the code implementation such as by clear feature-relevant naming conventions. The degree of Code coverage should be known, and should meet or exceed the standard required. The unit test cases should have been executed and the increment proven to work as expected.

Peer reviews ought to be done. (Note: If pair programming is used, a separate peer review session might not be required). Source code is checked into the configuration management system with appropriate, peer-reviewed comments added. The source code should have been merged with the main branch and the automatic deployment into elevated environments should be verified.

Test Complete

Functional testing should be done. This includes both automated testing and manual exploratory testing, and a test report should have been generated. All outstanding defects (or incidents such as build issues) should be elicited and resolved, or accepted by the team as not being contra-indicative to release. Regression testing has been completed, and the functionality provided in previous iterations has been shown to still work. Performance, security, and user acceptance testing should have been done, and the product should be shown to work on all required platforms.

DEFICIT FOR RELEASE

"Done" criteria which are needed to effect a release, but which cannot yet be observed, constitute a deficit. They should be enumerated here (e.g. by moving them out of the Definition of Done).

Aus <https://www.scrum.org/resources/blog/walking-through-definition-done>
