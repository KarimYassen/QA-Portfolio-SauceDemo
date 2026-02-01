# JIRA Bug Report 001

**Title:** Checkout: First Name changes when entering Last Name (problem_user)  
**Priority:** High  
**Module:** Checkout  
**Environment:** SauceDemo (Web)

## Summary
During checkout, the First Name field changes automatically when typing in the Last Name field, preventing correct user information entry.

## Steps to Reproduce
1. Login using `problem_user / secret_sauce`
2. Add "Sauce Labs Backpack" to cart
3. Open cart → Click Checkout
4. Enter First Name: Karim
5. Enter Last Name: Yassen

## Expected Result
Last Name field accepts input normally and First Name remains unchanged.

## Actual Result
First Name field changes automatically when entering Last Name and Last Name does not accept input correctly.

## Evidence
Screenshot attached in Jira ticket.
