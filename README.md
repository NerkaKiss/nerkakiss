# Hi there 👋, I'm Nerijus — QA Automation Engineer

![Profile views](https://komarev.com/ghpvc/?username=nerkakiss&style=flat-square)
[![Portfolio](https://img.shields.io/badge/Portfolio-nerkakiss.github.io-blue?logo=githubpages)](https://nerkakiss.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/nerijuskisieliauskas/)
[![GitHub](https://img.shields.io/badge/GitHub-NerkaKiss-black?logo=github)](https://github.com/NerkaKiss)

> 💡 “Breaking things so users don't have to.”

---

## 👤 About Me

QA Automation Engineer with previous experience in programming, IT support, and B2B sales. After several years in sales, I made a deliberate return to technology through software testing, combining hands-on QA training with independent automation projects to strengthen and demonstrate my technical skills.

I independently design and build maintainable UI and API automation frameworks using **Playwright with Java, TypeScript, and Python**, as well as **REST Assured with Java**.

My portfolio includes automated testing against live production platforms in logistics, e-commerce, and railway booking, along with public API automation. The projects use Page Object Model architecture, reusable fixtures and components, externalized test data, authenticated storage state, GitHub Actions CI/CD, Allure reporting, and failure diagnostics.

I use **OpenCode** and **Playwright MCP** to accelerate implementation, application exploration, and debugging while retaining ownership of framework architecture, test design, technical decisions, and final validation.

My B2B sales background gives me a practical understanding of stakeholder needs, business risk, and customer impact — perspectives that influence how I prioritize what to test and why.

Currently open to QA Automation Engineer opportunities.

---

## 🧰 Automation Stack

### Test Automation

![Playwright](https://img.shields.io/badge/Playwright-Automation-45ba4b?logo=playwright)
![Selenium](https://img.shields.io/badge/Selenium-WebDriver-green?logo=selenium)
![pytest](https://img.shields.io/badge/pytest-Test%20Framework-0A9EDC?logo=pytest)
![TestNG](https://img.shields.io/badge/TestNG-Test%20Framework-orange)
![POM](https://img.shields.io/badge/Page%20Object%20Model-Architecture-lightgrey)

### Programming Languages

![Java](https://img.shields.io/badge/Java-Programming-orange?logo=openjdk)
![TypeScript](https://img.shields.io/badge/TypeScript-Language-3178C6?logo=typescript)
![JavaScript](https://img.shields.io/badge/JavaScript-Language-yellow?logo=javascript)
![Python](https://img.shields.io/badge/Python-Language-blue?logo=python)

### API Testing

![REST Assured](https://img.shields.io/badge/REST%20Assured-Java%20API%20Testing-green)
![GraphQL](https://img.shields.io/badge/GraphQL-API-E10098?logo=graphql)
![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange?logo=postman)
![JSON](https://img.shields.io/badge/JSON-Test%20Data-lightgrey?logo=json)

### AI-Assisted QA & Development

![OpenCode](https://img.shields.io/badge/OpenCode-AI%20Coding%20Agent-black)
![Playwright MCP](https://img.shields.io/badge/Playwright%20MCP-Application%20Exploration-45ba4b?logo=playwright)
![ChatGPT](https://img.shields.io/badge/ChatGPT-AI%20Assistance-74AA9C?logo=openai)
![GitHub Copilot](https://img.shields.io/badge/GitHub%20Copilot-AI%20Coding-black?logo=githubcopilot)
![Claude](https://img.shields.io/badge/Claude-AI%20Assistance-D97757)

Used for application exploration, implementation support, debugging, refactoring, test scenario analysis, code review, and CI troubleshooting. All AI-assisted changes are manually reviewed, tested, and validated.

### CI/CD, Reporting & Development Tools

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088FF?logo=githubactions)
![Maven](https://img.shields.io/badge/Maven-Build%20Tool-c71a36?logo=apachemaven)
![Allure](https://img.shields.io/badge/Allure-Test%20Reports-orange)
![Git](https://img.shields.io/badge/Git-Version%20Control-red?logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Repository%20Hosting-black?logo=github)
![Chrome DevTools](https://img.shields.io/badge/Chrome%20DevTools-Debugging-lightblue?logo=googlechrome)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-IDE-darkblue?logo=intellijidea)
![VS Code](https://img.shields.io/badge/VS%20Code-Editor-blue?logo=visualstudiocode)
![PyCharm](https://img.shields.io/badge/PyCharm-IDE-green?logo=pycharm)
![Ruff](https://img.shields.io/badge/Ruff-Python%20Linting-D7FF64)

---

## 🚀 Projects

### 🛠 DPD Shipment Automation Framework — Playwright, Java

End-to-end test automation for [esiunta.dpd.lt](https://esiunta.dpd.lt), DPD Lithuania's live shipment ordering platform, using **Java, Playwright, TestNG, and Maven**.

**Automated test suite:** 21 E2E tests — 5 smoke and 16 regression.

**Key features:**

- Page Object Model architecture with `PageManager`
- Separate base test setup for authenticated and unauthenticated scenarios
- Positive login and JSON-driven negative login validation
- Reusable authenticated Playwright storage state
- Shipment option selection and shipment form validation
- Parcel locker selection coverage
- PUDO-to-PUDO shipment flow up to the summary and payment stage
- Externalized test data and environment configuration
- Smoke and regression execution through TestNG groups
- Controlled sequential execution selected after identifying shared account-level backend state conflicts that made parallel runs unreliable
- One automatic retry for transient live-site failures
- Failure diagnostics with screenshots and Playwright traces
- Allure reporting through Maven
- GitHub Actions CI/CD pipeline
- OpenCode-assisted implementation and CI troubleshooting, with technical decisions and validation performed manually
- Responsible production testing strategy with a focused suite, no destructive actions, and no real payment submission

[![GitHub](https://img.shields.io/badge/GitHub-java--playwright--dpd--shipping--flow-black?logo=github)](https://github.com/NerkaKiss/java-playwright-dpd-shipping-flow)

---

### 🛠 DEPO E-Commerce Test Automation — Playwright, TypeScript

End-to-end UI and API test automation for [online.depo-diy.lt](https://online.depo-diy.lt), a live Lithuanian e-commerce platform, using **Playwright and TypeScript**.

**Automated test suite:** 32 tests — 15 positive and 17 negative.

**Key features:**

- Page Object Model architecture with `PageManager`
- Custom Playwright fixtures
- Strictly typed test data using TypeScript interfaces
- Reusable authentication and cookie consent setup
- UI coverage for authentication, product browsing, search, cart, checkout, categories, and navigation
- GraphQL cart validation using Playwright `APIRequestContext`
- GraphQL-based cart cleanup to improve test isolation
- JSON-driven data management
- Smoke, regression, API, and UI tagging strategy
- Parallel execution support
- GitHub Actions CI/CD pipeline
- Allure reporting
- Playwright MCP used for application exploration and locator discovery
- OpenCode used to accelerate implementation, debugging, and framework refactoring
- All AI-assisted changes manually reviewed and validated

[![GitHub](https://img.shields.io/badge/GitHub-depo--playwright--ts-black?logo=github)](https://github.com/NerkaKiss/depo-playwright-ts)

---

### 🛠 LTG Link Railway Booking Automation — Playwright, Python

End-to-end test automation for [ltglink.lt](https://ltglink.lt), the Lithuanian railway ticket booking platform, using **Playwright, Python, and pytest**.

**Automated test suite:** 24 tests — 8 smoke and 16 regression.

**Key features:**

- Page Object Model architecture with `PageManager`
- Reusable pytest fixtures
- Reusable date picker component
- Authenticated user flows using Playwright storage state reuse
- Train route search and station autocomplete
- One-way and round-trip booking flows
- Disabled past-date validation
- Multi-step booking coverage up to the payment stage
- Seat selection and additional-service flows
- Mobile viewport checks for search, navigation, and responsive behavior
- Smoke, regression, and mobile test execution using pytest markers
- GitHub Actions smoke, regression, and scheduled nightly runs
- Failure diagnostics with screenshots, traces, and videos
- Automatic retries for transient live-site failures
- Allure reporting
- Ruff-based Python code quality checks
- Selective use of Playwright MCP for flow exploration
- OpenCode-assisted debugging, refactoring, and CI troubleshooting
- Responsible production testing strategy designed to minimize unnecessary traffic

[![GitHub](https://img.shields.io/badge/GitHub-ltglink--playwright--python-black?logo=github)](https://github.com/NerkaKiss/ltglink-playwright-python)

---

### 🛠 E-Commerce API Test Automation — REST Assured, Java

API test automation framework for [DummyJSON](https://dummyjson.com/) using **REST Assured, Java 21, TestNG, and Maven**.

**Automated test suite:** 17 tests — 11 positive and 6 negative.

**Key features:**

- Modular framework architecture
- Reusable API wrapper layer
- Request and response DTOs
- Centralized configuration layer
- Reusable utilities and test data handling
- Authentication API coverage
- Product listing, retrieval, and search scenarios
- Cart retrieval, creation, update, and deletion scenarios
- Positive and negative API validation
- End-to-end business flow covering login → current user → product search → add product to cart
- Dynamic data handling without hardcoded test dependencies
- Soft assertions for comprehensive response validation
- TestNG groups for flexible suite execution
- Maven-based test execution
- GitHub Actions CI/CD pipeline
- Allure reporting
- LLM-assisted analysis used to identify missing positive, negative, and business-flow scenarios
- All selected scenarios manually implemented, reviewed, and validated

[![GitHub](https://img.shields.io/badge/GitHub-qa--dummyjson--restassured-black?logo=github)](https://github.com/NerkaKiss/qa-dummyjson-restassured)

---

## 🎓 Training & Certifications

- **Manual & Automation Software Testing — 160 hours**  
  Vilnius Coding School

- **Playwright with Python: Web & API Testing — 60 hours**  
  Udemy

- **Playwright with TypeScript: Web & API Testing — 70 hours**  
  Udemy

- **REST API Test Automation with REST Assured — 24 hours**  
  Udemy

- **Playwright Path — 12 hours**  
  Test Automation University by Applitools

- **Postman API Fundamentals Student Expert — 6 hours**  
  Postman

- **BrowserStack Learning Paths — 20 hours**  
  Live, App Live, Percy Visual Testing, and TestNG Automation

- **JavaScript & Node.js for Testers, QA Engineers and SDETs — 12 hours**  
  Udemy

- **Bash Mastery: The Complete Guide to Bash Shell Scripting — 12 hours**  
  Udemy

---

## 📫 Let's Connect

Open to QA Automation opportunities, collaboration, and continuous improvement in software quality and test automation practices.

[![Portfolio](https://img.shields.io/badge/Portfolio-nerkakiss.github.io-blue?logo=githubpages)](https://nerkakiss.github.io/)
[![Email](https://img.shields.io/badge/Email-nerkai%40gmail.com-blue?logo=gmail)](mailto:nerkai@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-nerijuskisieliauskas-blue?logo=linkedin)](https://www.linkedin.com/in/nerijuskisieliauskas/)
[![GitHub](https://img.shields.io/badge/GitHub-NerkaKiss-black?logo=github)](https://github.com/NerkaKiss)
