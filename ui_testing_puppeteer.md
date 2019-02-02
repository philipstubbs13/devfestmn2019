# Resilient UI System Testing with Puppeteer

* Presenter
  * Mike Eastes
    * Senior Software Engineer, Code42
    * mike.eastes@code42.com
    * <https://github.com/meastes>
* Automated Tests can...
  * Catch JS errors that happen at runtime
  * Catch edge cases in ui behavior
  * Validate that data makes it from the API to being rendered.
  * Validate correctness of rare UI states (server errors)
* Terminology
  * Unit test - Validates the correctness of a single unit of work (function, interface, etc.)
  * System test - Validates the correctness of a complete system including all modules (ie. visual components, state management, "glue code").
  * Acceptance Test - Validates the correctness of complete service including all APIs and applications.
* System vs Acceptance
  * System tests
    * Mock all data from server APIs
    * Execute in a headless browser
    * Validate correctness of the UI only
  * Acceptance tests
    * Require real data
    * Often execute in a full browser
    * Validate correctness of entire system
* One big system test advantage: Shorter Feedback Cycles
* Test Pyramid
  * E2E
  * System
  * Unit
* Puppeteer - node library provided by google that allows you to control a webpage inside of a headless instance of chrome.
* Generate images and PDFs from webpages
* Compatible with any JS test runner
* Fully emulates a keyboard and mouse
* The ability to slow down tests for easier debugging.
* All in one solution: Cypress
  * screenshots/videos
  * utility functions
  * test debugger
  * downsides
    * less control
    * more bugs
    * need to write tests in different ways (no variables)
* Avoid hard-coded wait times
* Improvements
  * Builds complete in less than half the time.
  * Tests run on every PR
* Continuous Delivery - Following development practices that allow you to release at any time.

