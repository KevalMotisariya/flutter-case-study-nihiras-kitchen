# Nihira’s Kitchen – Food Ordering & Subscription App  
Flutter Case Study | Client Project

## Overview
Nihira’s Kitchen is a **production Flutter application** built for a restaurant to manage **food ordering and tiffin subscription services** through a mobile-first experience.

The app allows users to browse menus, place one-time food orders, or subscribe to recurring tiffin deliveries with flexible date and time selection. It is live on the **Google Play Store** and currently in its early growth stage.

> **Note:** Source code is private due to client confidentiality and NDA.  
> This repository documents **execution, architecture, and real-world business logic**, not demo code.

---

## Role & Ownership
**Sole Flutter Developer**

- Independently developed the **entire Flutter application**
- Integrated **all REST APIs** provided by the backend system
- Worked directly with a **restaurant client**
- Responsible for:
  - UI/UX implementation
  - API integration
  - Payment flow
  - Production-ready Play Store builds
- Admin panel existed separately and was not part of my scope

This project reflects **end-to-end individual ownership**.

---

## Development Timeline
**Mid 2024 – Late 2025**

- Initial development → production release
- Iterative improvements aligned with business requirements

---

## Application Scale
- Live on Google Play Store
- **500+ downloads** (early-stage product)
- Active users placing real food orders
- Monetization via **online payments only**

---

## Core Features

### Authentication & User Flow
- Secure user authentication
- Address selection for deliveries
- User-specific order handling

---

### Menu & Ordering System
- Category-based menu browsing:
  - Tiffin subscriptions
  - Food orders
  - Quick meals
  - Today’s specials
- Cart and checkout system
- Multiple packaging options with dynamic pricing

---

### Tiffin Subscription Module
- Users select:
  - Date range
  - Meal type (Lunch / Dinner / Both)
- Recurring food delivery until subscription period ends
- Subscription-based order logic separate from one-time orders

---

### One-Time Order Module
- Standard cart-based ordering
- Single checkout flow
- Designed for instant food orders

---

### Payment Integration
- **Razorpay payment gateway**
- Secure online payment handling
- Order confirmation post successful payment

---

## Architecture & Technical Details
- **State Management:** GetX
- API-driven Flutter application
- Clear separation of:
  - UI
  - Controllers
  - API services
- Designed to support:
  - Multiple order types
  - Subscription-based workflows
  - Future feature expansion (order tracking, notifications)

---

## Key Technical Challenge

### Subscription-Based Order Logic
**Problem**
- Managing recurring tiffin deliveries with date ranges and meal-time selection
- Required separate business logic from one-time food orders

**Solution**
- Designed distinct order flows:
  - Subscription orders
  - Single cart orders
- Ensured pricing, checkout, and backend payloads remained consistent
- Built a scalable structure to support future subscription enhancements

---

## Business Impact
- Enabled the restaurant to:
  - Accept online orders
  - Manage recurring tiffin customers
  - Reduce manual phone-based ordering
- Improved customer convenience with:
  - Scheduled meal deliveries
  - Digital payments
  - Centralized order handling

---

## Live Application
Google Play Store:  
https://play.google.com/store/apps/details?id=com.softhub.niharakitchen

---

## Final Note
This case study demonstrates the ability to:

- Build **real-world business applications**
- Handle transactional workflows and payments
- Translate restaurant operations into scalable mobile logic
- Deliver production-ready Flutter apps as a solo developer

The focus is **execution, reliability, and business value**.
