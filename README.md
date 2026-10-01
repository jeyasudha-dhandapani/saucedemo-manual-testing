# SauceDemo Manual Testing Project

Manual testing project performed on [Swag Labs](https://www.saucedemo.com), a demo e-commerce application, to practice real-world QA skills including test case design, test execution, and defect tracking.

## What I Did
- Analyzed the application and designed **21 test cases** covering 5 modules
- Executed all test cases manually and recorded Pass/Fail results
- Identified **1 defect** and logged it in JIRA with full details
- Practiced the complete Defect Lifecycle (New → In Progress → Done)

## Modules Tested
- Login (positive, negative, and boundary scenarios)
- Product Sort (price and alphabetical sorting)
- Cart (add/remove products)
- Checkout (form validation and order flow)
- Logout (including browser back-button security check)

## Results
| Metric | Count |
|---|---|
| Total Test Cases | 21 |
| Passed | 20 |
| Failed | 1 |
| Bugs Logged in JIRA | 1 |

## Bug Found
**Incorrect/duplicate product images displayed for `problem_user`**
When logging in with the `problem_user` account, all products displayed the same incorrect image instead of their own unique images. Logged in JIRA as SCRUM-5.

## Tools Used
- **Excel** – Test case design and execution tracking
- **JIRA** – Defect logging and lifecycle tracking
- **saucedemo.com** – Application under test

## Files in this Repository
- `SauceDemo_Test_Cases.xlsx` – All 21 test cases with steps, expected/actual results
- `Test_Summary_Report.docx` – Summary of testing scope, results, and findings
- `Bug_ProblemUser_WrongImages.png` – Screenshot showing the bug
- `JIRA_Bug_Board.png` / `JIRA_Bug_Details.png` – Bug tracked in JIRA

## Author
**Jeyasudha D**
[LinkedIn](https://www.linkedin.com/in/jeyasudha-dhandapani-259734374) | [GitHub](https://github.com/jeyasudha-dhandapani)
