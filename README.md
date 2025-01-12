# Add-to-Cart Field Test Cases

This document outlines test cases to validate the functionality, performance, and user experience of the Add-to-Cart feature in an e-commerce application.

---

## Test Case 1: Add Single Product to Cart
**Test Case ID**: TC_CART_01  
**Objective**: Verify that a single product can be added to the cart successfully.  
**Steps**:  
1. Navigate to a product page.
2. Click the "Add to Cart" button.
3. Open the cart page.
**Expected Result**: The selected product is displayed in the cart with correct details (name, price, quantity).

---

## Test Case 2: Add Multiple Products to Cart
**Test Case ID**: TC_CART_02  
**Objective**: Ensure multiple products can be added to the cart.  
**Steps**:  
1. Add multiple products from different categories to the cart.
2. Open the cart page.
**Expected Result**: All selected products are displayed in the cart with accurate details.

---

## Test Case 3: Update Product Quantity
**Test Case ID**: TC_CART_03  
**Objective**: Verify the ability to update the quantity of a product in the cart.  
**Steps**:  
1. Add a product to the cart.
2. Navigate to the cart page.
3. Update the product quantity.
**Expected Result**: The cart updates the total price and reflects the new quantity.

---

## Test Case 4: Remove Product from Cart
**Test Case ID**: TC_CART_04  
**Objective**: Ensure a product can be removed from the cart.  
**Steps**:  
1. Add a product to the cart.
2. Navigate to the cart page.
3. Click the "Remove" button next to the product.
**Expected Result**: The product is removed from the cart, and the cart updates accordingly.

---

## Test Case 5: Empty Cart Validation
**Test Case ID**: TC_CART_05  
**Objective**: Validate the behavior when the cart is empty.  
**Steps**:  
1. Ensure the cart is empty.
2. Navigate to the cart page.
**Expected Result**: A message is displayed (e.g., "Your cart is empty"), and no product details are shown.

---

## Test Case 6: Add Out-of-Stock Product
**Test Case ID**: TC_CART_06  
**Objective**: Verify behavior when attempting to add an out-of-stock product to the cart.  
**Steps**:  
1. Navigate to a product page for an out-of-stock product.
2. Click the "Add to Cart" button.
**Expected Result**: A message is displayed (e.g., "This product is out of stock") and the product is not added to the cart.

---

## Test Case 7: Price Calculation Accuracy
**Test Case ID**: TC_CART_07  
**Objective**: Ensure the total price is calculated accurately in the cart.  
**Steps**:  
1. Add multiple products with different quantities to the cart.
2. Verify the subtotal and total prices.
**Expected Result**: Prices are calculated correctly, considering quantity and any applicable discounts.

---

## Test Case 8: Performance of Add-to-Cart Functionality
**Test Case ID**: TC_CART_08  
**Objective**: Validate the performance of the Add-to-Cart feature under load.  
**Steps**:  
1. Simulate multiple users adding products to the cart simultaneously.
2. Monitor response times.
**Expected Result**: The Add-to-Cart feature performs within acceptable response times without errors.

---

## Test Case 9: Add-to-Cart Responsiveness
**Test Case ID**: TC_CART_09  
**Objective**: Ensure the Add-to-Cart functionality works on all devices.  
**Steps**:  
1. Test the feature on desktop, tablet, and mobile devices.
**Expected Result**: The Add-to-Cart button is functional and responsive on all devices.

---

## Test Case 10: Persist Cart Items Across Sessions
**Test Case ID**: TC_CART_10  
**Objective**: Verify that cart items persist after the user logs out and logs back in.  
**Steps**:  
1. Add products to the cart while logged in.
2. Log out and log back in.
3. Open the cart page.
**Expected Result**: The cart retains the previously added items.
