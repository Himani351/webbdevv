# Web Development Final Project

## Project Title
StyleHub - Modern E-Commerce website

## 👤 Student Information
**Name:** Himani 
**College ID :** 2024KUEC2013  
**Batch:** C1

 ## 🚀 Deployment Link (Mandatory)
Live Project Link:  
https://himani351.github.io/webbdevv/
---

## 🔐 Login Details (If Required)
If your project includes login, provide demo credentials:

**Username / Email:** 123h@gmail.com

**Password:** 1234

---

## 📝 Project Description
Write a clear description of your project here.  
Explain what the project does, its purpose, and the features included.

PROJECT OVERVIEW

StyleHub is a lightweight, responsive, Single Page Application (SPA) designed to replicate the core user experience of major e-commerce platforms like Flipkart. Built entirely with HTML5, Vanilla JavaScript, and Tailwind CSS, it demonstrates how to build complex, state-driven interfaces without the overhead of heavy frontend frameworks.
The project focuses on a "Flipkart-style" UX, featuring a persistent vertical sidebar for filtering, a rich product detail view, and instant cart management interactions.

KEY FEATURES

A. User Interface & Experience (UI/UX)

Responsive Design: Fully fluid layout that adapts from desktop (sidebar + grid) to mobile (stacked layout).
Vertical Filtering Sidebar: A sticky, left-aligned sidebar allowing users to filter by Categories, Price Range, Brand, and Customer Ratings.
Toast Notifications: Custom-built, animated feedback popups for actions like "Added to Cart" or "Login Successful".

B. Product Browsing

Dynamic Grid System: Products are rendered dynamically from a structured JavaScript object array.
Rich Product Cards: Displays product image, truncated title, discount percentage, rating badges, and review counts.
Detailed Product View: Includes zoom-friendly imagery, interactive Size Selector, and sticky action buttons.

C. Shopping Cart System

State Management: Tracks items, quantities, and selected sizes.
Dynamic Calculation: Real-time calculation of Subtotals, Discounts, and Final Amounts.
Quantity Controls: Users can adjust quantities or remove items instantly without page reloads.

D. Authentication & Session Management

Mock Authentication: Functional Login and Signup forms.
Data Persistence: Uses localStorage to persist user sessions.
Conditional Rendering: Navbar changes dynamically based on auth state.

TECHNICAL STACK

Markup: Semantic HTML5.
Styling: Tailwind CSS (via CDN).
Uses utility classes for layout, spacing, and typography.
Custom color palette: "Flipkart Blue" (#2874f0) and "Call-to-Action Orange" (#fb641b).
Logic: Vanilla JavaScript (ES6+).
SPA Architecture: Uses a custom Maps() function to switch views without server round-trips.
Object-Oriented Structure: Logic encapsulated in a single app object.

TECHNICAL ARCHITECTURE HIGHLIGHTS

View Switching: Uses ID-based visibility toggling (e.g., #view-home, #view-detail).
Component Rendering: Functions generate HTML strings using Template Literals based on data state.
Event Delegation: Interactions pass IDs to functions to find specific data objects dynamically.
FUTURE SCOPE

Backend Integration (NodeJS/Express).
Implementation of active filtering logic.
Payment Gateway integration (Stripe/Razorpay).
---


*(If no login is required, remove this section)*
