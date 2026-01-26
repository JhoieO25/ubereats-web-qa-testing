# Bug 001 – Add to Cart Rapid Clicks Cause Page Freeze and Tab Crash

## Summary
Rapid consecutive clicks on the **Add to Cart** button cause the UberEats web page to freeze and eventually crash the browser tab.

## Environment
- Application: UberEats Web Ordering Platform  
- Browser: Google Chrome Version 144.0.7559.60  
- Operating System: Windows 10  
- Test Type: Functional UI Testing  
- Network Condition: Normal network  

## Preconditions
- User is on a restaurant menu page  
- At least one menu item is visible and available for ordering  
- User is not logged out  

## Steps to Reproduce
1. Open a restaurant menu page  
2. Select any menu item  
3. Rapidly click the **Add to Cart** button multiple times in quick succession  
4. Observe the page behavior  

## Expected Result
- The system should handle rapid consecutive clicks gracefully  
- The UI should remain responsive  
- Only valid cart updates should occur   

## Actual Result
- The page becomes unresponsive  
- The browser tab freezes and eventually crashes    

## Severity
High – Causes application instability and loss of user session  

## Priority
High – Affects core ordering flow and user experience  

## Evidence
- Loom video showing Add to cart freeze and tab crash https://www.loom.com/share/0d0746ef49874327966e5ff30f1d54de
<img width="127" height="107" alt="image" src="https://github.com/user-attachments/assets/a00d78f7-88d9-497d-af28-ef2a74896faf" />

## Notes
This defect was observed during stress interaction testing of the cart functionality.  
