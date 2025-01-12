# Manual-Testing-of-OrangeHRM-Login-Page
This project focuses on manual testing of the login page for a Human Resource Management (HRM) system. The aim is to validate the login functionality, error handling, and user interface responsiveness. Tools used include Excel for test case creation and defect tracking.
## Repository Content
1. `Test_Plan.docx`: Detailed test plan for manual testing of the OrangeHRM login page.
2. `Project_Details.xlsx`: Includes:
   - Project details (sprint date, browser versions, build information).
   - Bug report (identified issues, severity, and status).
   - Decision table for test scenarios.
   - Test scenarios for login functionality.

## Bug Report Example
| **SR NO.** | **Bug ID** | **Summary** | **Steps to Reproduce** | **Expected Result**                     | **Actual Result**                        | **Severity** | **Priority** | **Reported By**      | **Date**  | **Status** |
|------------|------------|-------------|-------------------------|-----------------------------------------|-----------------------------------------|--------------|--------------|----------------------|-----------|------------|
| 1          | BUG001     | Username validation does not handle "admin" case-insensitively | 1. Navigate to the login page. 2. Enter variations of "admin" (e.g., Admin, ADMIN). 3. Enter a valid password and click Login. | Error message: "Username is restricted." | Username variations of "admin" are accepted as valid input. | High         | High         | Shakshi Kejriwal     | 1/6/2025  | Open       |

---
