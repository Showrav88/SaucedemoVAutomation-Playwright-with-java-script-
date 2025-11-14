# SaucedemoVAutomation-Playwright-with-java-script-

[View Allure Report](https://showrav88.github.io/SaucedemoVAutomation-Playwright-with-java-script-/)

##1️⃣ Project Overview

This is an end-to-end automation test: the user logs in with valid credentials, adds one product to the cart, verifies the product name, and logs out of the project for SauceDemo.

###The project demonstrates:

1.UI automation use Playwright with JavaScript.

2.Allure Reporting for beautiful test reports

3.CI/CD setup using GitHub Actions

4.Automated GitHub Pages deployment for Allure reports

5.Page Object Model (POM) design pattern for test maintainability

##2️⃣ Technologies & Tools Used

-JavaScript – main programming language

-Playwright Test – automation framework

-Allure Playwright & Allure Commandline – test reporting

-Node.js – runtime environment

-Git & GitHub – version control & CI/CD

GitHub Actions – workflow automation

-GitHub Pages – host Allure reports publicly

-Rimraf – clean old reports before generating new ones

## 📂 Project Structure

```bash
SaucedemoV/
├─ tests/                        # All your test specs
│  └─ specs/
│      └─ userLogin.spec.js
├─ pages/                        # Page classes (POM)
│  └─ login.js
├─ objects/                      # Object repositories (locators)
│  ├─ loginObjects.js
│  └─ addToCartObjects.js
├─ resources/                    # Test data / utilities
│  └─ testData.js
├─ playwright.config.js          # Playwright configuration
├─ package.json                  # Project dependencies & scripts
├─ node_modules/
├─ allure-results/               # Generated Allure results (ignored in git)
├─ allure-report/                # Generated Allure HTML report (ignored in git)
├─ .github/
│  └─ workflows/
│      └─ playwright.yml         # GitHub Actions workflow
├─ .gitignore
├─ README.md

```
##4. Installation & Setup
1. Clone the repo
   
```bash
git clone https://github.com/Showrav88/SaucedemoVAutomation-Playwright-with-java-script-.git
cd SaucedemoV

```
2. Install dependencies
```bash
npm ci
npx playwright install --with-deps

```
3. Install Allure (if not installed globally)
```bash
npm install -D allure-playwright allure-commandline

```
##4️⃣ Install Utility Package
```bash
npm install --save-dev rimraf

```
##5️⃣ Running Project Locally
1. Clean previous reports:
```bash
npm run allure:clean

```
2.Run tests and generate results:
```bash
npm run test:allure

```
3.Generate HTML report:
```bash
npm run allure:generate
```
4.Open report in browser:
```bash
npm run allure:open

```
##6️⃣CI/CD & GitHub Pages

-Workflow triggers on push to main branch

-Playwright tests run automatically in GitHub Actions

-Allure HTML report is generated and deployed to GitHub Pages

Reports available here:
[Allure Report](https://showrav88.github.io/SaucedemoVAutomation-Playwright-with-java-script-/)

##7️⃣Contact / Author

Author: Showrav Karmakar



