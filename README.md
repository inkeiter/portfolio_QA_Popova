# 🧪 QA Engineer Portfolio | Functional, API & Test Automation

> 🇷🇺 Русская версия: [README.ru.md](README.ru.md)

Hi! I'm a junior QA Engineer with 6 months of commercial experience testing web services. This repository collects my hands-on work in test design, API testing, and UI + API test automation, including the use of AI tools.

## 🛠 Skills

**Testing:** functional, regression, and acceptance testing; test design techniques (equivalence partitioning, boundary value analysis)  
**API & tools:** Postman, Swagger, DevTools, Jira  
**Test automation:** Java (Selenide, RestAssured, JUnit 5), Python (Playwright, pytest)  
**CI & version control:** Git, GitHub, GitHub Actions, AppVeyor  
**Data:** SQL (PostgreSQL), simple queries to verify data correctness  
**AI tools:** ChatGPT and Claude for writing SQL queries and generating simple automated tests; I review and run all generated code myself

## 📂 Projects

**1. E2E Tests (UI + API) for a Banking Application**
*   **Stack:** Java 11, Selenide, RestAssured, JUnit 5, JavaFaker, Gradle, CI (AppVeyor)
*   **Description:** Automated tests for the user interface (UI) and the API of a test banking application.
*   **Key features:**
    *   Page Object pattern
    *   UI tests: login, form filling, navigation and element checks
    *   API tests: requests to endpoints, validation of responses and JSON structure
    *   Valid random test data for forms generated with JavaFaker (no hardcoded values)
    *   Continuous integration with AppVeyor: the app server starts and tests run in headless mode on every push
*   🔗 [View code on GitHub](https://github.com/inkeiter/e2e-testing-java-selenide)

**2. QA Documentation**
*   **Stack:** Jira (bug report format), Markdown, ISTQB terminology
*   **Description:** Manual testing artifacts that show requirements analysis, test design, and clear documentation.
*   **Key features:**
    *   Structured test cases with steps, test data, and expected results
    *   Checklists for functional testing of web forms (positive and negative scenarios)
    *   Sample defect reports in Jira format with severity, priority, and steps to reproduce
*   🔗 [View documentation on GitHub](https://github.com/inkeiter/qa-documentation)

**3. AI-Assisted E2E Testing (Playwright + Python)**
*   **Stack:** Python, Playwright, pytest, GitHub Actions, AI assistant (Claude)
*   **Description:** A pet project exploring how generative AI can speed up test automation, with every result reviewed by a human.
*   **Key features:**
    *   Two E2E tests for the Sauce Demo practice site: a successful login and a negative scenario with a wrong password
    *   Stable locators and Playwright auto-waiting assertions, no `sleep`
    *   CI with GitHub Actions
    *   Writing prompts, running the generated code, and debugging errors both in the AI output and in the test itself
    *   Learning Playwright from scratch with the help of AI tools
*   🔗 [View code on GitHub](https://github.com/inkeiter/saucedemo-ai-e2e)

## 🔗 About me

**Experience:** 6 months of commercial QA on web services (client-server architecture, API)  
**English:** reading technical documentation (B1–B2)  
**LinkedIn:** [linkedin.com/in/ekaterina-popova-94ab30423](https://www.linkedin.com/in/ekaterina-popova-94ab30423)  
**Telegram:** [@keiterin](https://t.me/keiterin)
