# Securebank-manual-Testing
# SecureBank Manual Testing Project - README

## Comprehensive Documentation for Quality Assurance Processes

### Project Overview
This repository outlines the end-to-end manual testing framework developed for SecureBank, a secure online banking platform. The project ensures robustness, usability, and security across critical modules, including user authentication, transaction processing, and cross-browser compatibility.

## Documentation Structure
The Excel file **My Project.xlsx** is organized into seven sheets:

### 1. Test Plan
- High-level testing strategy with objectives, scope, and a reference to the full test plan PDF.

### 2. Mind Maps
- Visual representation of the application’s architecture and feature relationships.

### 3. Test Scenarios
- Prioritized scenarios (e.g., TS_001: Validate Navbar functionality) mapped to **181 test cases**.

### 4. Test Cases
- Detailed steps, expected/actual results, and statuses (**Passed/Failed/Not Executed**).
- **Modules covered**: User Registration, Login, Transactions, UI/UX, Search, Store Management.

### 5. Test Summary Report
- **Results**: 162 Passed (**89.5%**), 16 Failed (**8.83%**), 6 Not Executed.
- **Testing scope, limitations, and environment details** (Google Chrome vXX.X).

### 6. Bug Reports
- Critical defects logged with severity, steps to reproduce, and resolution status (e.g., **Logo redirect failure**).

### 7. Test Metrics
- Quantitative insights: **Test coverage, defect density, and efficiency metrics**.

## Key Features Validated
- **Security**: Multi-factor authentication, SQL injection prevention, encrypted password handling.
- **Functionality**: End-to-end transaction flows, file uploads, and real-time balance updates.
- **UI/UX**: Responsive design across Chrome, Firefox, Edge, and Safari.
- **Edge Cases**: Blank form submissions, invalid file formats, and boundary value testing.

## Testing Methodology
1. **Requirement Analysis**: Aligned test scenarios with the **Functional Requirements Specification (FRS)**.
2. **Test Design**: Authored **181 test cases** using real-world user workflows.
3. **Execution**: Manual validation with a focus on critical user journeys and edge cases.
4. **Defect Management**: Logged bugs with screenshots, prioritized fixes, and retested resolutions.
5. **Reporting**: Delivered metrics for stakeholder transparency and continuous improvement.

## Bug Tracking Highlights
- **#SL_01**: Logo redirect failure (**Priority: P1 | Severity: High**).
- **#SL_05**: Password reset workflow error (**Priority: P0 | Severity: Critical**).
- **#SL_09**: Real-time data sync failure in Store Management (**Priority: P1 | Severity: High**).

## Acknowledgments
- **Md Sabiul Islam (Sahal Vhai)**: For strategic guidance on complex test scenarios.
- **Ehsanul Alam Sabbir Vhai**: For rigorous review of test documentation and defect prioritization.

## Future Enhancements
- Expand test coverage to include **API and performance testing**.
- Implement automation using **Selenium or Cypress** for regression suites.

## Contact
For any inquiries or contributions, reach out to:
**Kazi Mostafa Moymim**  
Email: [your-email@example.com]  
GitHub: [yourusername]

