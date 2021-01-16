# Protractor

## Project
On this project regression testing is currently a manual process, which is a laborious, monotonous process. In collaboration with the lead developer, an automated regression test suite was setup to reduce manual effort it takes to run regression tests, and allow testing to focus on new features. The choice was made to use Protractor mainly because all new features are written in Angular. Unfortunatley the test scripts cannot be published due to proprietary.

### Key Features
* Use of page objects
* Tests for both Angular, and non-Angular pages
* Written using typescript

## Lesson Learned
* Don't try to convert existing manual regression tests into automated test scripts
* Create API automated tests where possible to avoid flakiness when going through UI 
