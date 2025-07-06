# OpenCart Manual Testing Project

## Project Overview
This is a personal learning project designed to gain hands-on experience in manual testing for my first job application. I conducted comprehensive testing on the OpenCart e-commerce platform (https://demo.opencart.com/) to validate its core functionalities, executed 100 test cases, logged 6 critical bugs, and documented the process using industry-standard artifacts. The project was completed between June 20, 2025, and July 7, 2025, as a step toward securing an entry-level QA position.

## Objective
- Validate 10 key functionalities: Register, Login, Logout, Search, Add to Cart, Wishlist, Homepage, My Account, Checkout, and Shopping Cart.
- Execute 100 test cases (10 per functionality) to ensure stability and usability.
- Identify, log, and report defects to demonstrate practical testing skills.
- Create a portfolio-ready project for GitHub and resume inclusion.

## Project Details
- **Duration**: June 20, 2025 – July 7, 2025
- **Environment**: Tested on Chrome and Opera browsers, OpenCart demo site (https://demo.opencart.com/)
- **Tools Used**: 
  - Microsoft Excel (Test Scenarios, Test cases, RTM, Bug report, Execution Result)
  - Microsoft Word (Test Summary Report, Test Plan, FRS)
  - Snipping Tool (Screenshots)
  - Google Sheets (Publicly accessible test data)

- **Learning Resources**: Inspired by YouTube tutorials, adapted to OpenCart context.

## Test Summary
### Test Execution Results
| **Functionality**            | **Total Test Cases** | **Passed** | **Failed** | **Pass %** |
|-------------------------------|----------------------|------------|------------|------------|
| Register                     | 10                   | 8          | 2          | 80%        |
| Login                        | 10                   | 10         | 0          | 100%       |
| Logout                       | 10                   | 9          | 1          | 90%        |
| Search                       | 10                   | 10         | 0          | 100%       |
| Add to Cart                  | 10                   | 9          | 1          | 90%        |
| Wishlist                     | 10                   | 10         | 0          | 100%       |
| Homepage                     | 10                   | 10         | 0          | 100%       |
| My Account                   | 10                   | 9          | 1          | 90%        |
| Checkout                     | 10                   | 10         | 0          | 100%       |
| Shopping Cart                | 10                   | 9          | 1          | 90%        |
| **Total**                    | **100**              | **94**      | **6**      | **94%**    |

- **Overall Pass Rate**: 94%
- **Failed Test Cases**: 6 out of 100 (6%)


## Bugs Reported
| **Bug ID**      | **Description**                              | **Severity** |
|------------------|----------------------------------------------|--------------|
| Opencart_BUG_01 | User can register with an invalid phone number | Medium       |
| Opencart_BUG_02 | Red * sign for mandatory fields missing except Privacy Policy | Low          |
| Opencart_BUG_03 | Logout from one device doesn’t log out on another device | Medium       |
| Opencart_BUG_04 | Invalid quantity (-1) for Add to Cart shows success message | Critical     |
| Opencart_BUG_05 | My Account from Site Map logs out with invalid token warning | High         |
| Opencart_BUG_06 | Invalid quantity (-1) update in Shopping Cart shows success message | High         |

- **Defect Logging**: Bugs were documented with steps to reproduce, expected vs. actual results, and screenshots.

## Artifacts
- **[Test Summary Report]: Detailed overview of test results and conclusions.**
- **[Test Plan]: Outline of testing approach and scope.**
- **[FRS (Functional Requirement Specification)]: Requirements tested during the project.**
- **[Test Scenarios]: High-level test scenarios for each functionality.**
- **[RTM (Requirement Traceability Matrix)]: Mapping of requirements to test cases and status.**
- **[Test Cases]: Detailed test cases with steps and results.**
- **[Test Cases Execution]: Execution status of all 100 test cases.**
- **[Bug Report]: Detailed defect logs with severity & Priority.**



## Folder Structure
- **Documentation/**: High-level project documents (PDFs).
- **Test_Artifacts/**: Testing data and execution records (Excel files With Google Spreadsheets links).
- **Defects/**: Bug Report (Excel file With Google Spreadsheets link)

## Learning Outcomes
- Mastered test case design, execution, and defect logging for e-commerce platforms.
- Developed skills in creating RTM, Test Plans, and Test Summary Reports.
- Gained practical experience with manual testing processes, preparing me for entry-level QA roles.
- Learned to organize and present project artifacts on GitHub for portfolio purposes.

## Skills Acquired
- Manual Testing
- Test Case Creation and Execution
- Defect Logging and Reporting
- Requirement Traceability
- Microsoft Excel, Word, and Google Sheets
- Basic GitHub Usage

## Contact
- **Name**: Bharg Goswami
- **Email**: bharg.goswami.msu@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/Bharg-Goswami

## Acknowledgments
Special thanks to Pavan Sir’s YouTube tutorials for guidance, which I adapted to create this project. Grateful for the support in building my QA foundation.

## Future Improvements
- Retest failed functionalities after bug fixes.
- Explore automation testing with tools like Selenium.
- Add more test scenarios for edge cases.
