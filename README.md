# Automated tests

This repository contains solutions for Symphony Tasks

1. Playwright Automated API tests for Task One.
2. Automated UI tests for Task Two using playwright.

## Pre-requisites

- Node.js 16+

## Running tests locally

#### Clone this repository

```bash
git clone git@github.com/Imekan/symphony-task.git
```

#### navigate to the project directory

```bash
cd symphony-task
```

#### Install dependencies

```bash
npm install
```

#### Run test

To run the tests, run the following command. This command will run the tests, generate a report and open it on the browser.

```bash
npm run show-report-html
```

### Generate report
I integrated basic HTML reporting which is one of playwright's features  to generate a report after running the tests. To generate the report, run the following command after running the tests.

```bash
npm run show-report
```

 The report will be served in the `/test-results` directory.

 Alternatively, you can run the following command to open the default playwright report for individual tasks.

 ```bash
 npm run task1
 ```

```bash
 npm run task2
 ```

## Running tests in Github CI/CD

The CI/CD pipeline is configured in the `.gitlab-ci.yml` file to run the automated test on GitLab or Github using the playwright Docker runner.

To run the tests in Github CI/CD, push the code to the repository and the pipeline will be triggered automatically.

## Authors

[@Imekan Enang](https://www.github.com/Imekan/)|




