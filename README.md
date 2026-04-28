# 🧪 OrangeHRM Manual Testing Report

## Project Overview

| Field               | Details                        |
|---------------------|--------------------------------|
| **Project Name**    | OrangeHRM Demo                 |
| **Client**          | OrangeHRM Demo                 |
| **Reference Doc**   | FRS (Functional Requirements)  |
| **Created By**      | Yashasvi Bhati                 |
| **Application URL** | [OrangeHRM Live Demo](https://opensource-demo.orangehrmlive.com/) |

---

## 📁 Repository Structure

```
├── Manual_testing_1_.xlsx
│   ├── Test Scenario      → 95 test scenarios across all modules
│   ├── Test Cases         → Detailed step-by-step test cases
│   └── Final Sheet        → Summary / traceability matrix
└── README.md
```

---

## 📋 Modules Tested

| Module                  | Scenario IDs        | Description                                      |
|-------------------------|---------------------|--------------------------------------------------|
| **Login**               | TS_001 – TS_010     | Valid/invalid credentials, empty fields, UI      |
| **Dashboard**           | TS_011 – TS_015     | Widgets, quick launch, refresh, user profile icon|
| **Admin**               | TS_016 – TS_025     | Add/edit/delete users, search, pagination        |
| **Employee Management** | TS_026 – TS_035     | Add/edit/delete employees, photo upload, search  |
| **Leave**               | TS_036 – TS_045     | Apply, cancel, history, manager approval         |
| **Time**                | TS_046 – TS_050     | Timesheet creation, entry, edit, delete          |
| **Recruitment**         | TS_051 – TS_055     | Job vacancy, candidate registration & search     |
| **Performance**         | TS_056 – TS_058     | KPI creation, performance review                 |
| **Notification**        | TS_059 – TS_060     | Notification module verification                 |
| **Profile**             | TS_061 – TS_063     | Profile edit, password change                    |
| **UI Testing**          | TS_064 – TS_068     | Responsive design, alignment, fonts, icons       |
| **System Testing**      | TS_069 – TS_071     | Server response, page load, error pages          |
| **Logout**              | TS_072 – TS_074     | Logout redirect, session clearance               |
| **Search Functionality**| TS_075 – TS_077     | Employee, admin user, candidate search           |
| **Form Validation**     | TS_078 – TS_080     | Required fields, email, phone validation         |
| **File Upload**         | TS_081 – TS_083     | Upload, size & type validation                   |
| **Report Module**       | TS_084 – TS_085     | Report generation, file validation               |
| **Access Control**      | TS_086 – TS_087     | Role-based access, admin permissions             |
| **Edge Cases**          | TS_088 – TS_090     | Long input, special chars, multiple login tries  |
| **Browser Testing**     | TS_091 – TS_093     | Chrome, Firefox, Edge compatibility              |
| **Performance**         | TS_094 – TS_095     | Page load time, large data handling              |

**Total Test Scenarios: 95**

---

## 🔬 Test Cases (Sample)

| TC ID  | Scenario    | Description                                       | Status | Priority | Bug ID  |
|--------|-------------|---------------------------------------------------|--------|----------|---------|
| TC_001 | TS_001      | Login with valid username & invalid password      | ✅ Pass | —        | —       |
| TC_002 | TS_002      | Login with invalid username & valid password      | ❌ Fail | Medium   | BUG_001 |
| TC_003 | TS_003      | Login with valid credentials                      | ✅ Pass | —        | —       |
| TC_004 | TS_004      | Login with empty username & valid password        | ✅ Pass | —        | —       |
| TC_005 | TS_005      | Login with valid username & empty password        | ✅ Pass | —        | —       |
| TC_006 | TS_006      | Login with both fields empty                      | ✅ Pass | —        | —       |
| TC_007 | TS_007      | Password field masking                            | ✅ Pass | —        | —       |
| TC_008 | TS_008      | Login button is clickable                         | ✅ Pass | —        | —       |
| TC_009 | TS_009      | Error message for invalid credentials             | ✅ Pass | —        | —       |
| TC_010 | TS_010      | Forgot Password link redirects correctly          | ✅ Pass | —        | —       |

---

## 🐛 Bug Report

| Bug ID  | TC ID  | Description                                                    | Severity |
|---------|--------|----------------------------------------------------------------|----------|
| BUG_001 | TC_002 | System shows "Invalid credentials" instead of case-sensitivity message when using lowercase "admin" as username | Medium   |

---

## ✅ Test Execution Summary

| Metric              | Count |
|---------------------|-------|
| Total Scenarios     | 95    |
| Total Test Cases    | 10+   |
| Passed              | 9     |
| Failed              | 1     |
| Bugs Reported       | 1     |

---

## 🛠️ Test Environment

| Item         | Details                                           |
|--------------|---------------------------------------------------|
| Application  | OrangeHRM Open Source Demo                        |
| URL          | https://opensource-demo.orangehrmlive.com/        |
| Reference    | FRS (Functional Requirement Specification)        |
| Test Type    | Manual Functional Testing                         |
| Browsers     | Chrome, Firefox, Edge                             |

---

## 📌 How to Use This Report

1. Open `Manual_testing_1_.xlsx`
2. Navigate to the **Test Scenario** sheet to view all 95 scenarios organized by module
3. Navigate to the **Test Cases** sheet for detailed step-by-step execution with expected/actual results
4. Navigate to the **Final Sheet** for the traceability matrix linking requirements to test cases

---

## 👩‍💻 Author

**Yashasvi Bhati**  
Manual QA Tester  
Project: OrangeHRM Demo Application Testing
