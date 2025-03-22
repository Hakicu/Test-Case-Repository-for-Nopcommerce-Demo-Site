# 🔎 Search & Filter Test Cases (NopCommerce Demo Site)

This document contains test cases related to the search functionality and product filtering options on [demo.nopcommerce.com](https://demo.nopcommerce.com).

---

## TC-004: Product Search with Valid Keyword

**Test Case ID:** TC-004  
**Title:** Search for a product using a valid keyword  
**Test Type:** Functional Test  
**Precondition:** At least one product with the keyword exists in the store  
**Test Steps:**
1. Navigate to [demo.nopcommerce.com](https://demo.nopcommerce.com)  
2. In the search box, type `laptop`  
3. Press `Enter` or click the search icon  

**Expected Result:**  
- A list of products containing the word “laptop” should be displayed  
- The result count should be greater than 0  

---

##  TC-005: Product Search with Invalid Keyword

**Test Case ID:** TC-005  
**Title:** Search for a product using a non-existing keyword  
**Test Type:** Negative Test  
**Precondition:** The search keyword does not match any product  
**Test Steps:**
1. Navigate to the homepage  
2. Type `abcdefg123` in the search box  
3. Click the search button  

**Expected Result:**  
- The message “No products were found that matched your criteria.” should appear  

---

##  TC-006: Filter Products by Category

**Test Case ID:** TC-006  
**Title:** Filter products by a specific category  
**Test Type:** Functional Test  
**Precondition:** Products must exist in selected category (e.g., Electronics > Notebooks)  
**Test Steps:**
1. Go to the “Electronics” category from the top menu  
2. Select “Notebooks”  
3. Verify that only notebook-related products are shown  

**Expected Result:**  
- Only notebook products should be displayed  
- The breadcrumb should show “Electronics > Notebooks”

---

##  TC-007: Apply Price Filter

**Test Case ID:** TC-007  
**Title:** Filter products by price range  
**Test Type:** Functional Test  
**Precondition:** Products exist within the selected price range  
**Test Steps:**
1. Go to the “Computers” category  
2. On the left sidebar, select a price filter (e.g., "$1000 - $1200")  
3. Observe the listed products  

**Expected Result:**  
- Only products priced between $1000 and $1200 should be displayed  

---

 Note: Each test can be manually executed or automated depending on the testing tools used.
