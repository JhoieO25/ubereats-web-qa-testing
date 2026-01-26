# Test Summary & Closure Report – UberEats Web Ordering Platform

## 1. Test Objective

The objective of this testing cycle was to validate the functional usability, stability, and network resilience of key user-facing features on the UberEats web ordering platform.

The focus was on high-risk customer journeys related to menu browsing, cart operations, pricing, and behavior under varying network conditions.

## 2. Test Scope Summary

The following functional areas were tested:

- Location selection and delivery address handling  
- Restaurant and menu browsing  
- Add to cart, update cart, and remove items  
- Pricing and total calculation  
- Search functionality  
- Network behavior under:
  - Offline mode  
  - Slow 3G throttling  

Out-of-scope areas included payment processing and backend APIs.

## 3. Test Execution Summary

- Total Test Cases Designed: ~60  
- Test Cases Executed: 58  
- Passed: Majority  
- Failed: 2–3 critical / medium defects  

Testing was conducted manually using exploratory and scenario-based techniques.

## 4. Defect Summary

Key defects identified during testing included:

- UI freeze and browser tab crash when rapidly clicking **Add to Cart**  
- Missing quantity limit or confirmation for large item quantities  

These defects affect core ordering flows and may impact user experience and business risk.

## 5. Non-Functional Testing Summary

Non-functional testing was performed using Chrome DevTools to simulate:

- Offline network conditions  
- Slow 3G throttling  

This validated:

- UI responsiveness  
- Error handling under poor network conditions  
- Stability of cart behavior under network stress  

## 6. Test Conclusion

The application demonstrated stable behavior for standard user flows.

However, critical usability and stability issues were identified in high-interaction and edge-case scenarios, particularly around cart operations.

It is recommended that:

- UI event handling be improved for rapid interactions  
- Business rules be added to limit or confirm unusually large quantities  

## 7. Test Closure

All planned test cases were executed.  
All high and medium defects were documented with reproduction steps and evidence.

## Sign-off

Tester: Joy Oghogho Omorogiuwa  
Role: Junior QA Engineer  
Certification: ISTQB CTFL  
Date: November, 2025  
