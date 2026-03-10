🍔 Food Delivery App (Expo + React Native)

A modern Food Delivery Mobile Application built using Expo & React Native, featuring user authentication, product browsing, cart management, favorites, payment flow, order tracking, and feedback system — all powered by AsyncStorage for local persistence.

🚀 Project Overview

This project is a complete frontend-based food delivery app created for learning, practice, and demonstration purposes.
It simulates real-world food delivery app functionality including:

User Registration & Login

Food Browsing by Categories

Cart & Favorites Management

Payment Flow

Order Tracking System

User Feedback & Rating

User Profile Management

The app uses Expo Router (file-based routing) for clean navigation and scalability.

🧠 Key Features
👤 User Authentication

User Registration & Login

User data stored locally using AsyncStorage

User-specific data handling (favorites, orders)

🏠 Home Screen

Food categories:

🍕 Pizza

🍔 Burger

🍟 French Fries

🍗 Chicken

🌯 Rolls

🥤 Drinks

🥙 Kabab

Grid-based food items

Clean UI with images & prices

❤️ Favorites (Wishlist)

Add / Remove items from favorites

Favorites saved per user (email-based storage)

Separate Favorites Screen

Auto-refresh using useIsFocused

🛒 Cart System

Add items to cart

Quantity increment & decrement

Cart count badge

Cart data stored in AsyncStorage

💳 Payment Module

Dedicated Payment Screen

Order confirmation after payment

Simulated payment flow (frontend-based)

Payment status saved locally

(Designed to be easily extendable for real payment gateways in future)

🚚 Order Tracking System

Track order status:

Order Placed

Preparing

On the Way

Delivered

Real-time order status simulation

Separate Order Tracking Screen

⭐ Feedback & Rating

Users can submit feedback after order delivery

Rating system (stars / text feedback)

Feedback stored locally

Enhances user interaction & experience

👤 Profile Section

Displays logged-in user name

Optional profile image

Dynamic welcome message

User-specific data overview

🔄 Persistent Local Storage

Uses @react-native-async-storage/async-storage

Data remains saved even after app reload

Handles:

User data

Cart

Favorites

Orders

Feedback

🧩 Tech Stack
📱 Frontend

React Native

Expo

Expo Router (File-based routing)

🧠 State Management

React Hooks (useState, useEffect)

useIsFocused for auto-refresh
"# FoodDeliveryApp" 
