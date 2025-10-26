Defect Report: ShopWise E-commerce

Bug Tracking ID: SW-CART-001
Title: Cart Quantity Limit Error on 'Wireless Headphones'
Severity: High (P2 - Critical for inventory management)
Status: New / Open (Simulated: Awaiting fix from Development)

Product Information

Module: Shopping Cart

Version (SUT): 1.0

Environment: Chrome, Web & Mobile Emulation

Observed on: 2024-05-27

Description of Defect

When a user attempts to add more than 5 units of 'Wireless Headphones' to the cart, the application displays a generic "Error: Maximum quantity exceeded for this item!" message, despite the maximum allowed quantity not being specified in the requirement document. This indicates an unhandled hardcoded limit or incorrect API response that needs to be addressed.

Steps to Reproduce

Open shopwise_app.html in a web browser.

Ensure the Cart Count is 0.

Click the "Add to Cart" button for 'Wireless Headphones' five (5) times. (Cart count should be 5).

Click the "Add to Cart" button for 'Wireless Headphones' one (1) more time.

Actual Result (Bug)

On the 6th click, a red "Error: Maximum quantity exceeded for this item!" message appears. The cart count remains at 5. The application should either allow the item to be added or display a clear limit message before the user hits the error, based on defined inventory rules.

Expected Result

The item should be added successfully (if inventory permits), or a clear, non-generic message should be displayed indicating the maximum allowed quantity for that specific item.

Verification (Simulated Closure)

Date Verified: N/A (Awaiting fix)

Tester: Mayank Ahuja

Verification Notes: N/A