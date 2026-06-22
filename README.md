# Hi there 👋, I'm Nerijus — QA Automation Engineer

![Profile views](https://komarev.com/ghpvc/?username=nerkakiss&style=flat-square)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/nerijuskisieliauskas/)
[![GitHub](https://img.shields.io/badge/GitHub-NerkaKiss-black?logo=github)](https://github.com/NerkaKiss)

> 💡 "Breaking things so users don't have to."

---

## 👤 About Me

QA Automation Engineer focused on building maintainable UI and API test automation frameworks.

I work with **Playwright**, **TypeScript**, **Python**, **Pytest**, **Java**, **TestNG**, **REST Assured**, and **Maven**, covering real-world user journeys, API validation, test data handling, reporting, and CI/CD execution.

My portfolio includes automation projects across multiple stacks:

- **Java + Playwright + TestNG** for shipment ordering flows
- **Python + Playwright + Pytest** for train ticket booking flows
- **TypeScript + Playwright** for e-commerce UI and GraphQL/API validation
- **Java + REST Assured + TestNG** for API test automation

I apply **Page Object Model**, `PageManager` patterns, reusable fixtures/base tests, authenticated session handling, marker/group-based test execution, externalized test data, Allure reporting, screenshots, traces, retries, and GitHub Actions CI/CD.

My projects cover production-like and real live-system scenarios, including authentication, search, cart, checkout, shipment creation, booking flows, API validation, mobile UI checks, and responsible automation against third-party websites.

Background in programming and IT support, with strong problem-solving, communication, and continuous learning skills.

**#OpenToWork**

---

## 🧰 Automation Stack

### Test Automation

![Playwright](https://img.shields.io/badge/Playwright-Automation-45ba4b?logo=playwright)
![Selenium](https://img.shields.io/badge/Selenium-Testing-green?logo=selenium)
![Pytest](https://img.shields.io/badge/Pytest-Test%20Framework-0A9EDC?logo=pytest)
![TestNG](https://img.shields.io/badge/TestNG-Framework-orange)
![JUnit](https://img.shields.io/badge/JUnit-Testing%20Framework-blue?logo=junit5)
![POM](https://img.shields.io/badge/Page%20Object%20Model-Architecture-lightgrey)

### Programming

![TypeScript](https://img.shields.io/badge/TypeScript-Language-3178C6?logo=typescript)
![JavaScript](https://img.shields.io/badge/JavaScript-Language-yellow?logo=javascript)
![Java](https://img.shields.io/badge/Java-Programming-orange?logo=openjdk)
![Python](https://img.shields.io/badge/Python-Language-blue?logo=python)

### API Testing

![REST Assured](https://img.shields.io/badge/REST%20Assured-Java%20API%20Testing-green)
![GraphQL](https://img.shields.io/badge/GraphQL-API-E10098?logo=graphql)
![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange?logo=postman)

### CI/CD & Tools

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?logo=githubactions)
![Maven](https://img.shields.io/badge/Maven-Build%20Tool-c71a36?logo=apachemaven)
![Allure](https://img.shields.io/badge/Allure-Reports-orange)
![Git](https://img.shields.io/badge/Git-Version%20Control-red?logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Repository%20Hosting-black?logo=github)
![Jira](https://img.shields.io/badge/Jira-Issue%20Tracking-blue?logo=jira)
![Chrome DevTools](https://img.shields.io/badge/Chrome%20DevTools-Debugging-lightblue?logo=googlechrome)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-IDE-darkblue?logo=intellijidea)
![VS Code](https://img.shields.io/badge/VS%20Code-Editor-blue?logo=visualstudiocode)
![Ruff](https://img.shields.io/badge/Ruff-Python%20Linting-D7FF64)

---

## 🚀 Projects

### 🛠 DPD Shipping Flow - Java Playwright Automation Test Suite

End-to-end test automation for [esiunta.dpd.lt](https://esiunta.dpd.lt), DPD Lithuania's shipment ordering platform, using **Java + Playwright + TestNG + Maven**.

**Key features:**
- Page Object Model architecture with `PageManager`
- Separate base test setup for authenticated and unauthenticated scenarios
- Valid login and JSON-driven negative login validation
- Reusable authenticated Playwright storage state
- Shipment option selection and shipment form validation
- PUDO-to-PUDO shipment flow coverage until the summary/payment step
- Smoke and regression test groups with TestNG
- Externalized test data and environment configuration
- One automatic retry for transient live-site issues
- Failure diagnostics with screenshots and Playwright traces
- Allure reporting through Maven
- GitHub Actions CI/CD pipeline with E2E status badge
- Responsible production testing strategy: small focused suite, sequential execution, no destructive actions, and no real payment submission

**Current coverage:** 21 E2E tests

[![GitHub](https://img.shields.io/badge/GitHub-java--playwright--dpd--shipping--flow-black?logo=github)](https://github.com/NerkaKiss/java-playwright-dpd-shipping-flow)

---

### 🛠 LTG Link Playwright Python E2E Test Suite

End-to-end test automation for [ltglink.lt](https://ltglink.lt), the Lithuanian train ticket booking platform, using **Playwright + Python + Pytest**.

**Key features:**
- Page Object Model architecture with `PageManager` and reusable Pytest fixtures
- Authenticated user flows with Playwright storage state reuse
- Train route search, station autocomplete, date validation, and multi-step booking coverage
- Dedicated smoke, regression, and mobile test suites using Pytest markers
- Mobile viewport checks for search form, mobile menu, and route search behavior
- Responsible production testing strategy to avoid unnecessary traffic against a live third-party website
- CI/CD pipeline with GitHub Actions, scheduled regression runs, failure artifacts, and Allure reporting
- Ruff-based Python code quality checks

[![GitHub](https://img.shields.io/badge/GitHub-ltglink--playwright--python-black?logo=github)](https://github.com/NerkaKiss/ltglink-playwright-python)

---

### 🛠 Playwright E2E + API Automation Framework

End-to-end and API test automation for [online.depo-diy.lt](https://online.depo-diy.lt), a real Lithuanian e-commerce site, using **Playwright + TypeScript**.

**Key features:**
- Page Object Model architecture with `PageManager` and custom fixtures pattern
- UI automation for login, search, product, cart, checkout, categories, and navigation flows
- API testing with GraphQL cart validation through Playwright `APIRequestContext`
- Reusable authentication and cookie consent setup with storage state
- Smoke, regression, API, and UI tagging strategy
- CI/CD pipeline with GitHub Actions
- Allure reporting

[![GitHub](https://img.shields.io/badge/GitHub-depo--playwright--ts-black?logo=github)](https://github.com/NerkaKiss/depo-playwright-ts)

---

### 🛠 REST Assured API Automation Framework

API test automation framework for [DummyJSON](https://dummyjson.com/) using **REST Assured + Java 21 + TestNG**.

**Key features:**
- Modular architecture with API wrappers, request/response DTOs, config layer, and reusable utilities
- Authentication, products, search, cart, and end-to-end cart flow coverage
- Positive and negative API scenarios grouped with TestNG
- End-to-end cart flow test: login → current user → products → add product to cart
- Soft assertions for comprehensive response validation
- Dynamic data handling without hardcoded test dependencies
- CI/CD pipeline with GitHub Actions
- Allure reporting through Maven

[![GitHub](https://img.shields.io/badge/GitHub-qa--dummyjson--restassured-black?logo=github)](https://github.com/NerkaKiss/qa-dummyjson-restassured)

---

## 📫 Let's Connect!

Open to QA Automation opportunities, collaboration, and continuous improvement in test automation practices.

[![Email](https://img.shields.io/badge/Email-nerkai%40gmail.com-blue?logo=gmail)](mailto:nerkai@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nerijuskisieliauskas-blue?logo=linkedin)](https://www.linkedin.com/in/nerijuskisieliauskas/)
[![GitHub](https://img.shields.io/badge/GitHub-NerkaKiss-black?logo=github)](https://github.com/NerkaKiss)
