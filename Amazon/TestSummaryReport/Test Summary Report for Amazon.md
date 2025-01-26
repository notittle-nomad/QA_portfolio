**Test Summary Report for Amazon.com**

**1\. Introduction**

* **1.1 Purpose**

  * This report summarizes the testing process conducted on the Amazon.com website ([https://www.amazon.com/](https://www.amazon.com/)).  
  * The goal was to evaluate the website's functionality, usability, accessibility, and performance from an end-user perspective.  
* **1.2 Source Data**

  * Amazon.com is a leading e-commerce platform offering product browsing, purchasing, account management, order tracking, and various features like reviews, recommendations, and personalized accounts.  
* **1.3 Scope**

  * The testing scope covered the following areas:  
    * User Account Management (Login/Logout, Registration)  
    * Product Search & Filtering  
    * Product Detail Page  
    * Shopping Cart  
    * Checkout Process (excluding payment gateway integration)  
    * Platform Coverage (different browsers)  
    * Usability and Accessibility  
    * Performance and Scalability (loading time)  
* **1.4 Out of Scope**

  * Payment gateway integration/testing  
  * Seller-specific functionalities  
  * Backend performance testing (load testing, stress testing)  
  * Security testing (penetration testing)  
  * Mobile app testing  
  * A/B testing of UI elements

**2\. Testing Conditions**

* Stable internet connection  
* Access to Amazon.com website  
* Specified test environment (MacOS 15.1.1, Chrome 131.0.6778.266, Edge 132.0.2957.115, Firefox 134.0.1, Safari 20619.2.8.11.12)  
* Test accounts (Name: Name, email: freetestlog@ukr.net, password: Sweet16, phone:+380684264097)  
* Test tools: Browser developer tools, Jira, Testrail, Google Sheets, Google Docs 

**3\. Testing Strategy**

* **Methodology:** Waterfall model for a structured testing approach.

* **Testing Approach:** Black-box testing, focusing on user-centric functionality.

* **Testing Techniques:** Positive and negative testing to validate expected behavior and identify potential issues.

* **3.1 Testing Types**

  * Functional Testing: Positive, Negative, Boundary Value Analysis, Equivalence Partitioning.  
  * Integration Testing: Verifying interactions between website modules (e.g., search & product display, cart & checkout).  
  * System Testing:  
    * User Acceptance Testing (UAT)  
    * Cross-Browser Testing & Compatibility Testing  
    * Usability Testing  
    * Navigation Testing (intuitiveness)  
    * Interface Testing (clarity & consistency)  
    * Accessibility Testing (WCAG compliance)  
  * Performance Testing:  
    * Page Load Time Testing (Homepage, Search Results)  
    * Responsiveness Testing

**4\. Testing Schedule**

* Start Date: January 23, 2025  
* End Date: January 26, 2025  
* Duration: 4 days

**5\. Entry and Exit Criteria**

* **Entry:**  
  * Test environment set up  
  * Test data prepared  
  * Test cases written and reviewed  
* **Exit:**  
  * All planned test cases executed  
  * Identified defects reported in Jira (with reviewed status)  
  * Test summary report created

**6\. Results**

* **6.1 Summary**

  * Testing identified various successes and a few areas for improvement.

  * The website functioned well overall, with successful user account management, product search & filtering, adding items to cart, and checkout process.

  * Usability and accessibility testing revealed positive results for navigation, CTA visibility, and basic WCAG compliance.

  * Performance testing indicated acceptable page load times under normal conditions.

  * However, two key issues were identified:

    * Validation message is missing for empty search queries. (Bug reported in Jira)  
    * Layout misalignment and horizontal scrolling required (Bug reported in Jira)  
        
* **6.2 Detailed Results**  
  *Test Suits: 7*  
  *Total Test Cases: 30*  
  *Passed: 28*  
  *Failed: 2*

| Bug ID | Description | Priority | Status |
| ----- | ----- | :---: | :---: |
| BUG-001 | Validation message is missing for empty search queries.  | Critical | Open |
| BUG-002 | Layout misalignment and horizontal scrolling required  | High | Open |


**7\. Recommendations**

* Fix the bug related to empty search queries to improve user experience.  
* Investigate and address responsiveness issues to ensure optimal display across various devices.  
* Consider further accessibility testing with assistive technologies for a more comprehensive evaluation.

**8\. Conclusion**

The conducted testing covered a wide range of Amazon website functionalities, including account management, product search and filtering, shopping cart operation, and the checkout process (excluding payment system integration). The testing demonstrated high stability and correct operation of most key functions. Registration and authorization processes, searching for products by keywords, adding products to the cart, and proceeding to checkout were successfully tested. Satisfactory page load speeds were also confirmed.

However, two issues were identified: incorrect handling of empty search queries and problems with site responsiveness on different devices. These issues require correction to ensure uninterrupted site operation and improve user experience.

Overall, the Amazon website demonstrates positive testing results. It is recommended to pay attention to correcting the identified shortcomings to ensure high product quality.