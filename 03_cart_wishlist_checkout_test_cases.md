#  Cart, Wishlist & Checkout Test Cases (NopCommerce Demo Site)

This document includes test scenarios related to adding products to the cart or wishlist and completing the checkout process on [demo.nopcommerce.com](https://demo.nopcommerce.com).

---

##  TC-008: Add Product to Cart from Product Page

**Test Case ID:** TC-008  
**Title:** Successfully add a product to the shopping cart  
**Test Type:** Functional Test  
**Precondition:** User is on a product detail page  
**Test Steps:**
1. Navigate to a product detail page (e.g., Apple MacBook Pro 13-inch)  
2. Click the “Add to cart” button  

**Expected Result:**  
- A message “The product has been added to your shopping cart” should appear  
- The cart icon should be updated with the product count  

---

##  TC-009: Add Product to Wishlist

**Test Case ID:** TC-009  
**Title:** Add a product to the wishlist  
**Test Type:** Functional Test  
**Precondition:** User is logged in  
**Test Steps:**
1. Navigate to a product page  
2. Click the “Add to wishlist” button  

**Expected Result:**  
- A confirmation message should appear  
- The product should be visible in the user's wishlist  

---

##  TC-010: View Shopping Cart and Update Quantity

**Test Case ID:** TC-010  
**Title:** Update product quantity in the shopping cart  
**Test Type:** Functional Test  
**Precondition:** At least one product is already in the cart  
**Test Steps:**
1. Click on the “Shopping cart”  
2. Change the quantity to a new number (e.g., from 1 to 2)  
3. Click “Update shopping cart”  

**Expected Result:**  
- The quantity and total price should update accordingly  

---

##  TC-011: Proceed to Checkout (Guest)

**Test Case ID:** TC-011  
**Title:** Guest user proceeds to checkout  
**Test Type:** End-to-End Functional Test  
**Precondition:** At least one product is in the cart  
**Test Steps:**
1. Go to the shopping cart  
2. Click “Checkout”  
3. Choose “Checkout as Guest”  
4. Fill in billing, shipping, and payment info  
5. Confirm the order  

**Expected Result:**  
- The order should be placed successfully  
- A confirmation page with “Your order has been successfully processed!” should appear  

---

##  TC-012: Remove Product from Cart

**Test Case ID:** TC-012  
**Title:** Remove an item from the shopping cart  
**Test Type:** Functional Test  
**Precondition:** Product is already added to the cart  
**Test Steps:**
1. Go to the shopping cart  
2. Click the remove icon (trash bin)  
3. Click “Update shopping cart”  

**Expected Result:**  
- The product should be removed  
- The cart should display “Your Shopping Cart is empty!”  

---

 Tips: You can add screenshots, execution results (PASS/FAIL), or even link bug reports if a test fails during execution.
