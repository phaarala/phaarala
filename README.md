## Paul Haarala
QA Analyst · Denver, CO

I test web applications end to end: exploratory testing, test planning, test case design, cross-browser and multi-account execution, and defect reporting with full traceability from test case to Jira ticket, plus SQL analysis of test results and automated API and UI tests that run in CI. My programming foundation comes from Harvard's CS50x, where I've written programs in C, Python, SQL and JavaScript.

### Featured work

**[QA Testing Portfolio](https://github.com/phaarala/qa-testing-portfolio)**: four completed projects covering a full test cycle, from manual testing and SQL analysis of the results to automated API and UI tests that run on every push.

[![API tests](https://github.com/phaarala/qa-testing-portfolio/actions/workflows/api-tests.yml/badge.svg)](https://github.com/phaarala/qa-testing-portfolio/actions/workflows/api-tests.yml) [![UI tests](https://github.com/phaarala/qa-testing-portfolio/actions/workflows/ui-tests.yml/badge.svg)](https://github.com/phaarala/qa-testing-portfolio/actions/workflows/ui-tests.yml)

**1. [Manual testing](https://github.com/phaarala/qa-testing-portfolio/tree/main/01-manual-testing)** · SauceDemo e-commerce site · Jira, Chrome DevTools
- 53 test cases designed and executed, plus 88 smoke checks across 4 user accounts and 4 browser configurations
- 18 defects logged in Jira, including 2 critical checkout blockers, each traced to the test case that found it
- Test plan, exploratory session log, and a test summary report with exit criteria and a release recommendation

**2. [SQL test analytics](https://github.com/phaarala/qa-testing-portfolio/tree/main/02-sql-test-analytics)** · Project 1's results · SQLite
- Test results and defects modeled in a 4-table SQLite database (53 test cases, 141 executions, 18 defects)
- 8 SQL queries reproduce the test summary report: pass rate by feature, defects by severity and priority, and results by account and browser
- A traceability query confirms every failed test is linked to a Jira bug

**3. [API testing](https://github.com/phaarala/qa-testing-portfolio/tree/main/03-api-testing)** · Restful-Booker REST API · Postman, Newman, GitHub Actions
- 25 automated Postman tests covering all 8 endpoints of a booking API: chained create-to-delete flow, JSON schema checks, negative and data-driven tests
- 9 defects logged in Jira, including bookings saved with a text price or with checkout before check-in
- Runs with Newman on every push through GitHub Actions

**4. [UI test automation](https://github.com/phaarala/qa-testing-portfolio/tree/main/04-ui-automation)** · SauceDemo · Playwright, Python, pytest, GitHub Actions
- The 11 high-priority manual test cases automated with Playwright and pytest using the Page Object Model, each named with its manual test case ID
- Runs in Chromium, Firefox and WebKit on every push through GitHub Actions: 30 passed, 3 expected failures
- Known bugs tracked as strict expected failures linked to Jira, so the build stays green and the bug stays visible

**[CS50x Problem Sets](https://github.com/phaarala/cs50xproblemsets)** · Harvard's introduction to computer science · C, Python, SQL, JavaScript · 
*Marked private in accordance with CS50's academic honesty policy.
- Programs in C covering pointers, manual memory management, binary file I/O, image filters and a hash-table spell checker
- Identified three unlabeled sorting programs as bubble, merge and selection sort by timing them on sorted, random and reversed inputs
- Verified output against answer keys (all 28 spell-checker texts, all 20 DNA samples) and checked for memory leaks with Valgrind
- Solved a mystery in a 10-table SQLite database by intersecting nested subqueries, with every query logged
- Built a four-page personal website with Bootstrap: responsive navbar and project cards, a dark mode that persists across pages via `localStorage`, and a contact form handled in JavaScript

### Skills

**Testing:** Test planning · Test case design · Exploratory testing · Equivalence partitioning · Boundary value analysis · Cross-browser testing · Defect reporting and triage · Requirements traceability · API testing · UI test automation · Page Object Model

**Programming:** SQL · Algorithm analysis (Big O) · Data structures (linked lists, hash tables, trees) · Recursion · Memory management and debugging · DOM scripting · Responsive web design

### Tools

**Languages:** Python · SQL · C · JavaScript · HTML · CSS

**Testing and development:** Bootstrap · Playwright · pytest · Postman · Newman · GitHub Actions · Jira · SQLite · DB Browser for SQLite · Valgrind · clang · Make · Chrome DevTools · Google Sheets · GitHub

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
