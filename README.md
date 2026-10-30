## Paul Haarala
QA Analyst · Denver, CO

I test web applications end to end: exploratory testing, test planning, test case design, cross-browser and multi-account execution, and defect reporting with full traceability from test case to Jira ticket, plus SQL analysis of test results and automated API and UI tests that run in CI.

### Featured work

**[QA Testing Portfolio](https://github.com/phaarala/qa-testing-portfolio)**: a complete test cycle for a sample e-commerce application, from manual testing and SQL analysis of the results to automated API and UI tests that run on every push.

**Manual testing**
- 53 test cases designed and executed, plus 88 smoke checks across 4 user accounts and 4 browser configurations
- 18 defects logged in Jira, including 2 critical checkout blockers, each traced to the test case that found it
- Test plan, exploratory session log, and a test summary report with exit criteria and a release recommendation

**SQL test analytics**
- Test results and defects modeled in a 4-table SQLite database (53 test cases, 141 executions, 18 defects)
- 8 SQL queries reproduce the test summary report: pass rate by feature, defects by severity and priority, and results by account and browser
- A traceability query confirms every failed test is linked to a Jira bug

**API testing**
- 25 automated Postman tests covering all 8 endpoints of a booking API: chained create-to-delete flow, JSON schema checks, negative and data-driven tests
- 9 defects logged in Jira, including bookings saved with a text price or with checkout before check-in
- Runs with Newman on every push through GitHub Actions

**UI test automation**
- The 11 high-priority manual test cases automated with Playwright and pytest using the Page Object Model, each named with its manual test case ID
- Runs in Chromium, Firefox and WebKit on every push through GitHub Actions: 30 passed, 3 expected failures
- Known bugs tracked as strict expected failures linked to Jira, so the build stays green and the bug stays visible

### Skills

Test planning · Test case design · Exploratory testing · Equivalence partitioning · Boundary value analysis · Cross-browser testing · Defect reporting and triage · Requirements traceability · SQL · API testing · UI test automation · Page Object Model

### Tools

Playwright · Python · pytest · Postman · Newman · GitHub Actions · Jira · SQLite · DB Browser for SQLite · Chrome DevTools · Google Sheets · GitHub

### Certification

**Microsoft Junior QA/Software Tester Professional Certificate**, Coursera (2026) · [Verify](https://coursera.org/verify/professional-cert/SZLJ0I2LOBML)

<details>
<summary>6 courses</summary>

- Software Testing Fundamentals and Methodologies
- Manual Testing and Defect Management
- Test Planning, Execution and Analytics
- Automation, Advanced Testing, and AI
- End-to-End QA Testing Cycle
- Launching Your QA Career

</details>

### Contact

[LinkedIn](https://www.linkedin.com/in/paul-haarala/)
