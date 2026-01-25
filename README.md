# ubereats-web-qa-testing
# UberEats Web Ordering Platform – QA Functional & Network Testing

---

## 1. Project Overview

This repository contains a personal Quality Assurance (QA) practice project conducted on the publicly accessible **UberEats Web Ordering Platform**.

The objective of this project was to design and execute structured functional and network-related test cases on a live production application, identify edge-case behaviors, document defects using professional standards, and produce formal QA reports that demonstrate real-world software testing skills.

The project focuses on core user journeys such as restaurant discovery, menu browsing, cart operations, search functionality, and resilience under unstable network conditions.

**P.S:** This project is intended solely for **educational and portfolio demonstration purposes**.

---

## 2. Project Type

- Personal QA Portfolio Project  
- Manual Functional Testing  
- Exploratory Testing  
- Edge-Case & Stability Testing  
- Network Failure Simulation Testing  

This is **not** a commissioned project by Uber and does not represent internal testing activities.

---

## 3. Scope of Testing

### In Scope

- Delivery Address selection
- Restaurant listing and availability  
- Menu browsing and item details  
- Add to Cart functionality  
- Cart quantity updates  
- Pricing and subtotal calculations  
- Predictive search and suggestions  

### Out of Scope

- User authentication and login  
- Payment processing  
- Checkout and order placement  
- Backend services and internal APIs  
- Inventory validation  
- Delivery assignment and tracking  
- Mobile application testing  

---

## 4. Test Approach & Strategy

The testing approach combined **structured functional testing** with **exploratory and edge-case testing**.

Key aspects of the strategy included:

- Designing test scenarios based on core user flows  
- Executing happy-path, negative, and boundary-value test cases  
- Performing exploratory testing to uncover stability and UX issues  
- Simulating failure conditions using browser developer tools  
- Recording failed scenarios using loom screen recording for reproducibility  
- Logging defects in a Jira-style format  
- Producing formal Test Summary and Test Closure reports  

Testing was performed on a live production environment with care taken to avoid any interaction with private user data or sensitive flows.

---

## 5. Test Design Technique Used

The following test design techniques were applied:
 
- **Boundary Value Analysis** (e.g., quantity limits)  
- **Positive and Negative Testing**  
- **Edge-Case Testing** (rapid user input, extreme values)  
- **Exploratory Testing**    

These techniques were used to ensure both normal and abnormal user behaviors were covered.

---

## 6. Functional Areas Covered

- Restaurant discovery and listing  
- Menu rendering and item details  
- Add to Cart interactions  
- Cart quantity increment and decrement  
- Subtotal and pricing updates  
- Predictive search and suggestions  
- Handling of invalid search input  
- User feedback during asynchronous operations  

---

## 7. Non-Functional Testing (Network Conditions)

Basic non-functional testing was performed using **Chrome DevTools** to simulate adverse network conditions, including:

- Offline mode  
- Throttled network (Slow 3G)  
- Blocked API requests  

These tests were used to evaluate:

- Application behavior when network requests fail  
- UI stability during delayed responses  
- Error handling and user feedback  
- Resilience of Add to Cart and menu loading flows  

This helped uncover stability issues related to rapid input and lack of input throttling.

---

## 8. Tools & Technologies

- **Browser:** Google Chrome  
- **Testing Type:** Manual Functional Testing  
- **Documentation:** Microsoft Excel, Microsoft Word  
- **Defect Tracking:** Jira (simulated project)  
- **Evidence Recording:** Loom & snipping tool
- **Utilities:**  
  - Chrome DevTools (Network tab, Throttling, Request Blocking)  

---

## 9. Defects Identified

| ID      |                     Summary                                        | Severity | Priority |
|----     |--------------------------------------------------------------------|----------|----------|
| BUG-001 | Add to Cart causes UI freeze and browser tab crash on rapid clicks | High     | High     |
| BUG-002 | No quantity limit or confirmation for large item quantities        | Medium   | Medium   |

These defects highlight stability, usability, and business logic concerns in core cart interactions.

---

## 10. Deliverables in This Repository

This repository contains the following QA artifacts:

- **Test Cases**
  - Structured functional sample test cases in Excel format  

- **Bug Reports**
  - Individual Jira-style bug reports in Markdown format  

- **Summarized Reports**
  - Test Summary Report  
  - Test Closure Report  

- **Evidence**
  - Loom recording links for failed scenarios  

- **Documentation**
  - This README file describing scope, approach, and outcomes  

---

## 11. Key Learning & Impact

Through this project, I have developed the following skills and knowledge on:

- Writing formal BRD, User stories & Acceptance criteria, Test plans and Test scenario docs. 
- Designing structured functional test cases for a live application  
- Identifying stability issues caused by rapid user input  
- Applying edge-case and boundary testing effectively  
- Writing professional Jira-style bug reports  
- Producing formal Test Summary and Test Closure reports  
- Using network simulation to validate resilience and error handling  
- Understanding the importance of UX feedback in asynchronous operations  
- Practicing ethical testing and data sanitization on production systems  

This project helped me demonstrate the ability to test real-world systems responsibly and professionally.

---

## 12. Confidentiality Note

**Confidentiality & Ethics Statement**

This project was conducted strictly as a personal QA practice exercise on the publicly accessible UberEats web platform.

- No private user accounts were accessed  
- No personal data was collected, stored, or shared  
- No payment, authentication, or sensitive flows were tested  
- No internal systems, APIs, or proprietary information were accessed    

The contents of this repository are provided solely for **educational, knowledge and portfolio demonstration purposes** and do not disclose any confidential, proprietary, or sensitive information belonging to Uber Technologies, Inc.

This repository does not imply any affiliation with or endorsement by Uber.

---

## Author

**Joy Oghogho Omorogiuwa**  
QA Engineer – Manual & Functional Testing  
Postgraduate Student @ National College of Ireland | ISTQB Certified Tester – Foundation Level (CTFL), November 2025 

