# Protractor

## Project - DAF QLD
On this project regression testing is currently a manual process, which is a laborious, monotonous process. In collaboration with the lead developer, an automated regression test suite was setup to reduce manual effort it takes to run regression tests, and allow testing to focus on new features. The choice was made to use Protractor mainly because all new features are written in Angular. Unfortunatley the test scripts cannot be published due to proprietary.

### Key Features
* Use of page objects
* Folder structure:
  * Utilities
  * Page Objects
  * Test Cases 
* Tests for both Angular, and non-Angular pages
* Written using typescript
* Use of Git with Bitbucket for source control

## Lesson Learned
* Don't try to convert existing manual regression tests into automated test scripts
* Create API automated tests where possible to avoid UI flakiness
* Start small
