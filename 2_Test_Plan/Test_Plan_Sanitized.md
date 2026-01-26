# Test Plan — UberEats Web Ordering Platform (Sanitized)

## 1. Objective
The objective of this test plan was to define the approach, scope, resources, and schedule for functional and network-related testing of the UberEats web ordering platform.

This test plan guided the design and execution of test scenarios to validate core user flows and system behavior under varying network conditions.

## 2. Scope of Testing

### In Scope
- Location selection and delivery address handling  
- Restaurant discovery and listing  
- Menu browsing and item customization  
- Add to cart, update cart, remove items  
- Pricing and total calculation  
- Search functionality  
- Network behavior under:
  - Offline mode  
  - Slow 3G throttling  
  - Intermittent connectivity  

### Out of Scope
- Payment processing  
- Order fulfillment and delivery tracking  
- Driver and merchant applications  
- Internal admin systems  

## 3. Test Types

The following test types were performed:

- Functional Testing  
- UI Testing  
- Exploratory Testing  
- Negative Testing  
- Non-functional Testing:
  - Network resilience testing  
  - Client-side error handling  

## 4. Test Environment

- Application: UberEats Web Application  
- Browser: Google Chrome  
- Operating System: Windows  
- Tools:
  - Chrome DevTools (Network throttling, Offline simulation)  
  - Excel (Test case management)  
  - Loom (Defect evidence recording)  

## 5. Entry and Exit Criteria

### Entry Criteria
- Application accessible via public web  
- Test environment stable  
- Test scenarios approved  

### Exit Criteria
- All planned test cases executed  
- Critical and high severity defects documented  
- Test summary report prepared  

## 6. Risks and Assumptions

### Risks
- Production data may change during testing  
- Network simulation may not fully reflect real-world user environments  

### Assumptions
- Testing performed on a live production environment  
- No internal system access available  
- Only black-box testing techniques applied  

## 7. Deliverables

- Test scenarios and test cases (sanitized samples)  
- Defect reports (sanitized samples)  
- Test summary and closure report  
- Screen recording evidence (via Loom links)  

## Confidentiality Note

This document is a sanitized version of the original test plan.  
No proprietary internal documentation, credentials, or sensitive business logic is included.
