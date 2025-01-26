**Test Plan for Amazon (https://www.amazon.com/)**

***1\. Introduction***

*1.1 Purpose* 

The purpose of this test plan is to describe the testing process of the Amazon.com website. The document allows gaining an understanding of the planned testing activities for Amazon.com.

*1.2 Source data* 

Amazon.com is an e-commerce platform that allows users to browse and purchase products, manage orders, track shipments, and utilize other features such as reviews, recommendations, and personalized accounts.

*1.3 Scope* 

* User Account Management (Login/Logout, Registration)  
* Product Search & Filtering  
* Product Detail Page  
* Shopping Cart  
* Checkout Process (excluding payment gateway integration)  
* Platform Coverage (different browsers)  
* Usability and Accessibility (ensuring a user-friendly and accessible website that meets the needs of a diverse range of users, including those with disabilities)  
* Performance and Scalability (loading time)

*1.4 Out of Scope:*

* Payment gateway integration/testing  
* Seller-specific functionalities  
* Backend performance testing (load testing, stress testing)  
* Security testing (penetration testing)  
* Mobile app testing  
* A/B testing of UI elements


***2\. Conditions for Testing*** 

* A stable internet connection is required.  
* Access to the Amazon.com website must be available.  
* The specified test environment must be set up and operational.  
* Test accounts (if needed) must be created and available.  
* Test Tools:  
  * Browser developer tools (for inspecting elements and network requests)  
  * Jira (or similar bug tracking system), Testrail, Google Sheets, Google Docs.  
  * Test management tool (optional)  
* Environment:   
  OS: MacOS 15.1.1   
  Browsers: Chrome 131.0.6778.266, Edge 132.0.2957.115, Firefox 134.0.1, Safari 20619.2.8.11.12.

**3\. Testing Strategy** 

This section outlines the overall approach to testing the Amazon website, covering the types of testing, levels of testing, and other key considerations. 

Testing Methodology \- Waterfall model for a structured testing approach.

Employ a black-box testing strategy, focusing on the system's functionality from the user's perspective without delving into internal code.

Use the positive and negative testing to validate expected behavior under normal conditions and identify potential issues with invalid inputs or unexpected scenarios.

*3.1 Testing Types*

Functional Testing: 

* Positive Testing.  
* Negative Testing.  
* Boundary Value Analysis.   
* Equivalence Partitioning.

Integration Testing: 

* Verifying the interaction between different modules and components of the website (e.g., search and product display, adding to cart and checkout).

System Testing: 

* User Acceptance Testing (UAT)  
* Cross-Browser Testing. Compatibility Testing.

Usability Testing.  
Navigation testing: 

* Checking the intuitiveness of the website's navigation.

Interface testing: 

*  Assessing the clarity and consistency of the user interface.

Accessibility testing: 

* Checking compliance with accessibility guidelines (WCAG) for users with disabilities (e.g., screen reader compatibility, keyboard navigation).

Performance Testing: 

* Page load time testing:  
  *Homepage and Key Functional Pages (e.g., Cart, Checkout)*: Should load within 2 seconds under normal user load.  
  *Search Results Page:* Should display results within 3 seconds for up to 50 items.  
* Responsiveness testing.

***4\. Testing Schedule***

* Start Date: 23.01.2025  
* End Date: 26.01.2025  
* Testing Duration: 4 days

***5\. Entry and Exit Criteria***

Entry Criteria:

* Test environment is set up and accessible.  
  * Test data is prepared and available.  
  * Test cases are written and reviewed.

   Exit Criteria:

  * All planned test cases have been executed.  
  * All identified defects have been reported in Jira and their status has been reviewed (resolved, deferred, etc.).  
  * Test summary report has been created.

***6\. Final Results***

*6.1 Resume* 

The final report will include a comprehensive summary of the testing process, identified defects, and recommendations for improving the functionality and usability of Amazon.com from an end-user perspective.

***7\. Test Deliverables***

* Test Plan (this document)  
* Test Cases  
* Bug Reports (Jira)  
* Test Summary Report

***8\. Roles and Responsibilities***

* *QA Tester:* Alla Vorobei: Responsible for writing and executing test cases, reporting bugs, and providing test results.  
* *Test Lead:* \[optional\]: Responsible for overseeing the testing process, managing the test team, and reporting to stakeholders.