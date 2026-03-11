# DevLovers QA Testing

QA testing documentation, checklists, and bug reports for the DevLovers platform.

## Overview
This repository contains:

- **Checklists** — step-by-step QA checklists for login, leaderboard, About, Blog, and other sections.
- **Bug Reports** — short descriptions of found bugs with screenshots; full details in Google Sheets.
- **Screenshots** — visual proof of bugs or UI issues.

Testing covers:

- Manual testing of web functionality
- Regression testing
- Functional, UX, and network/console checks

## Beta Testing Documentation
All QA checklists and bug reports are stored in a separate file:

- [DevLovers Beta Testing Report](https://docs.google.com/spreadsheets/d/1ErFWru9Y4mnAHZ-r5-jo5OKCgD_70_IND56m2_5yU6k/edit?usp=sharing)

## Sample Bugs
Short description of selected bugs with screenshots:

- **Login (1.3)** — Required fields validation shows raw key  
  ![Login bug](<img width="602" height="661" alt="Login – Required Fields Validation" src="https://github.com/user-attachments/assets/601d26b3-badf-4df0-b6f2-e3ebe728217f" />)

- **Registration (1.9)** — Password rules show raw validation key  
  ![Registration bug](<img width="649" height="748" alt="Password rules shows raw validation key" src="https://github.com/user-attachments/assets/1ca7ae36-d578-40fc-bd3a-94db63c36981" />)

- **Forgot Password (1.14)** — Unregistered email shows success message  
  ![Forgot Password bug](<img width="674" height="423" alt="Forgot password" src="https://github.com/user-attachments/assets/62edbbd7-ca3a-4966-b3d8-28daa13e5cee" />)

- **Homepage / Network (7.2)** — React error #418 in JS requests  
  ![Network bug](<img width="1905" height="794" alt="React error #418 in JS requests" src="https://github.com/user-attachments/assets/7ec7be1f-0b55-4339-9edf-d540d4293582" />)

> More bugs and checklists are available in the Google Sheets linked above.

## Repository Structure
```text
DevLovers-QA/
├── docs/
│   └── devlovers-beta-testing-report.md  # Main QA report with links to checklists and bug reports
├── screenshots/
│   ├── login_form/
│   │   └── login_raw_key.png
│   ├── registration/
│   │   └── password_raw_key.png
│   ├── forgot_password/
│   │   └── unregistered_email.png
│   └── network/
│       └── react_error_418.png
