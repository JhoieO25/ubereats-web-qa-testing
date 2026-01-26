# Bug 002 – No Quantity Limit or Confirmation for Large Item Quantities

## Summary
The system allows users to add an excessively large quantity of the same item to the cart without any quantity limit or confirmation, which may lead to accidental or invalid orders.

## Environment
- Application: UberEats Web Ordering Platform  
- Browser: Google Chrome Version 144.0.7559.60  
- Operating System: Windows 10  
- Test Type: Functional UI Testing  
- Network Condition: Normal network  

## Preconditions
- User is on a restaurant menu page  
- An item is available for ordering  
- Cart is empty or contains existing items  

## Steps to Reproduce
1. Open a restaurant menu page  
2. Select any menu item  
3. Repeatedly click the **Add to Cart/+** button to increase the item quantity to a very large number (e.g., 20+, 50+, 100+)  
4. Open the cart and review the quantity  

## Expected Result
- The system should enforce a reasonable maximum quantity limit per item  
  **OR**  
- The system should prompt the user with a confirmation dialog for unusually large quantities  

## Actual Result
- The system allows unlimited quantity increases  
- No warning, validation, or confirmation is shown  
- Large quantities are added directly to the cart  

## Severity
Medium – Can lead to accidental high-value orders and poor user experience  

## Priority
Medium – Affects order accuracy and business risk  

---

## Risk & Impact
- Users may accidentally place very large orders  
- Increased risk of order cancellations and refunds  
- Potential financial and operational impact on restaurants  

---

## Notes
This defect highlights missing business rule validation for order quantity limits and lack of user safeguard for high-risk actions.
