# Lab 7 README

## Names
- **Name:** Aditya Jadhav
- **Partner Name:** N/A

## Screenshot
- [npm-test-run screenshot](screenshots\npm-test-screenshot.png) 

## Check Your Understanding

### 1. Where would you fit automated tests in the Recipe project development pipeline?
I would put automated tests inside a **GitHub Action that runs whenever code is pushed**. This is the best choice because it checks new changes automatically, catches bugs early, and helps keep the project stable as development continues.

### 2. Would you use an end-to-end test to check if a function is returning the correct output?
**No.** End-to-end tests are meant to test the full user flow of an application, not the exact output of a single function. For that, unit tests are a better fit.

### 3. What is the difference between navigation and snapshot mode?
**Navigation mode** audits the page from the beginning of the page load, so it is useful for measuring load performance and overall page behavior during startup. **Snapshot mode** audits the page in its current state, so it is better for checking the current DOM and accessibility issues, but it does not measure full page load behavior.

### 4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
1. Improve accessibility by increasing color contrast and making sure interactive elements have clearer labels.
2. Optimize images and other static assets so the page loads faster and performs better.
3. Improve SEO and best practices by adding stronger metadata and making sure all page elements follow recommended standards.