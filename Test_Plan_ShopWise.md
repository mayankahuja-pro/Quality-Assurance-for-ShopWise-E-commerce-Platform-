Test Plan: ShopWise E-commerce - Shopping Cart Module

Project: ShopWise E-commerce Platform
Module Under Test: Shopping Cart Functionality
QA Lead: Mayank ahuja
Date: 2024-05-27
Version: 1.0

1. Introduction & Objectives

This plan outlines the strategy for quality assuring the core Shopping Cart features to ensure users can seamlessly add, modify, and remove products before proceeding to checkout.

Key Objective: To verify that the Shopping Cart functions correctly across Web and Mobile views, maintaining data integrity and handling inventory constraints accurately.

2. Scope of Testing

In Scope

Out of Scope

Adding/Removing Items

Payment Gateway Integration

Quantity Updates

User Authentication (Login/Register)

Price Calculation/Subtotal

Search Filter Functionality

UI/UX responsiveness check (Web vs. Mobile)

Advanced Shipping Logic

3. Testing Types

Test Type

Description

Functional Testing

Verify all buttons, links, and cart logic work as required.

Usability Testing

Check for clear error messages, intuitive flow, and responsive design (Web & Mobile).

Data Integrity Testing

(SQL Focus) Verify cart updates correctly reflect in the backend/session data (simulated).

API Testing

(API Focus) Verify product details are correctly fetched from the mocked Product API.

4. Test Environment

Browser: Chrome (latest)

Operating System: Windows/macOS

Mobile View Simulation: Chrome DevTools Mobile Emulation (Simulated Android/iOS).

5. Entry and Exit Criteria

Entry Criteria: The front-end ShopWise application (shopwise_app.html) must be running and accessible.

Exit Criteria: All High/Medium priority test cases must be executed and passed, and all reported P1/P2 defects must be verified as fixed.