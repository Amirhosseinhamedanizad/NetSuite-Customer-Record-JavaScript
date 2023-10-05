# NetSuite-Customer-Record-JavaScript

NetSuite Customer Record Creation with HTML and JavaScript

NetSuite Customer Record Creation with HTML and JavaScript

## Introduction

This assignment demonstrates the creation of a simple HTML form that allows users to enter customer information, such as first name, last name, and email. The assignment showcases how JavaScript can be used to simulate the process of creating a customer record in NetSuite, a popular cloud-based business management software. While this example does not directly interact with a real NetSuite instance, it illustrates the concepts and techniques that could be used for integrating web forms with NetSuite.

## How to Use

1. Open the `index.html` file in a web browser.

2. Fill out the form with customer information, including first name, last name, and email.

3. Click the "Create Customer" button.

4. The JavaScript code will simulate the creation of a customer record, and the created customer's data will be displayed on the web page.

## Note

This assignment provides a simplified example for educational purposes. In a real-world scenario, integration with NetSuite would involve setting up appropriate API calls to communicate with a NetSuite instance securely. The example code here is meant to illustrate the basic concepts of form submission and data display.

Feel free to customize and extend this code for your own use or as a learning exercise.

1. **User Interaction**: The HTML file contains a simple form that allows users to input customer information: first name, last name, and email.

2. **Event Listener**: The JavaScript code includes an event listener that listens for a click event on the "Create Customer" button in the form.

3. **Form Data Collection**: When the "Create Customer" button is clicked, the event listener triggers a function that collects the user-entered data from the form fields (first name, last name, and email).

4. **Simulated API Call**: The collected data is passed to a function called `createCustomerRecord`, which is simulated for demonstration purposes. In a real NetSuite integration, this function would make an API call to NetSuite to create a customer record with the provided data.

5. **Data Display**: In this simulated example, the `createCustomerRecord` function simply displays the customer data on the web page. It generates a message that includes the first name, last name, and email of the "created" customer.

6. **Output Display**: The output is displayed in a `<div>` element with the `id="output"` on the web page.

7. **Completion**: The user sees the customer data displayed on the web page, simulating the successful creation of a customer record in NetSuite.

This code is a simplified demonstration and does not actually interact with a real NetSuite instance. Instead, it illustrates the fundamental concepts of user input, data collection, and simulated API interactions in the context of creating a customer record, which can be a starting point for more complex integrations with NetSuite.
