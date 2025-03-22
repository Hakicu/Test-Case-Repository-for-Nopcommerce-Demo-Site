# Nopcommerce Demo Site Test Case Repository

This repository contains a collection of test cases for the **Nopcommerce Demo Site**. It is designed to assist in automated testing and validation of various functionalities available on the Nopcommerce platform. The test cases are organized by category and intended to ensure the quality and stability of the demo site.

## Table of Contents

- [Authentication Test Cases](#authentication-test-cases)
- [Search & Filter Test Cases](#search-filter-test-cases)
- [Cart & Wishlist Checkout Test Cases](#cart-wishlist-checkout-test-cases)
- [Bug Report and Test Result](#bug-report-and-test-result)
- [Other Information](#other-information)

## Authentication Test Cases

This section includes test cases related to authentication functionalities on the Nopcommerce demo site. The relevant test cases are listed in **01_authentication_test_cases.md**.

### Test Case 1: User Login
- **Description**: Verify if the user can log in with valid credentials.
- **Preconditions**: User account exists in the demo system.
- **Test Steps**:
  1. Go to the login page.
  2. Enter valid username and password.
  3. Click the login button.
- **Expected Result**: User is successfully logged in and redirected to the dashboard.

### Test Case 2: Invalid Login Attempt
- **Description**: Verify if the user is unable to log in with invalid credentials.
- **Preconditions**: User account exists in the demo system.
- **Test Steps**:
  1. Go to the login page.
  2. Enter an invalid username or password.
  3. Click the login button.
- **Expected Result**: Error message is displayed indicating incorrect credentials.

## Search & Filter Test Cases

This section includes test cases related to search and filter functionalities on the Nopcommerce demo site. The relevant test cases are listed in **02_search_filter_test_cases.md**.

### Test Case 1: Search by Product Name
- **Description**: Verify if the user can search for a product by its name.
- **Preconditions**: The product exists in the demo system.
- **Test Steps**:
  1. Go to the homepage.
  2. Enter the product name in the search bar.
  3. Click the search button.
- **Expected Result**: The search results show the product with the matching name.

### Test Case 2: Filter Products by Category
- **Description**: Verify if the user can filter products by category.
- **Preconditions**: Multiple products are available in different categories.
- **Test Steps**:
  1. Go to the product listing page.
  2. Select a category from the filter options.
  3. Apply the filter.
- **Expected Result**: The products listed are filtered by the selected category.

## Cart & Wishlist Checkout Test Cases

This section includes test cases for the cart and wishlist functionalities. The relevant test cases are listed in **03_cart_wishlist_checkout_test_cases.md**.

### Test Case 1: Add Item to Cart
- **Description**: Verify if the user can add an item to the shopping cart.
- **Preconditions**: The product exists in the demo system.
- **Test Steps**:
  1. Go to the product page.
  2. Click the "Add to Cart" button.
  3. Verify that the item is added to the cart.
- **Expected Result**: The product appears in the shopping cart.

### Test Case 2: Checkout Process
- **Description**: Verify if the user can proceed through the checkout process.
- **Preconditions**: The cart contains at least one item.
- **Test Steps**:
  1. Go to the shopping cart page.
  2. Click the "Proceed to Checkout" button.
  3. Complete the checkout steps (billing, shipping, payment).
- **Expected Result**: The user successfully completes the checkout process.

## Bug Report and Test Result

This section contains details of any bugs encountered during testing, as well as the results of the tests. The relevant test case is listed in **04_bug_report_and_test_result.md**.

### Bug Report and Test Case Results
- **Description**: A report of the bugs encountered and the test case results.
- **Test Steps**:
  1. Execute each test case.
  2. Document any issues encountered.
  3. Record the result of each test (Pass/Fail).
- **Expected Result**: A comprehensive report of the test results and any bugs found during the testing process.

## Other Information

### Bugs or Issues
If you encounter any bugs or issues while testing the Nopcommerce demo site, please report them in the **Issues** section of the repository. Provide the following details when reporting bugs:
- Description of the issue
- Steps to reproduce
- Expected result vs. actual result
- Screenshots or logs (if applicable)

### Known Issues
- Some checkout features may not work with certain browsers. Please ensure you are using a compatible browser for best results.
- User login may experience intermittent delays due to server-side processing.

### Contact Information
If you have any questions or would like to contribute to this repository, please contact me via GitHub issues or hakicu@gmail.com.

## Contributing

If you would like to contribute to this repository, please fork the repository and create a pull request with your changes. Contributions are welcome!

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
