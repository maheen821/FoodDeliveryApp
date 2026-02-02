🍔 Food Delivery App (Expo + React Native)

A modern Food Delivery Mobile Application built using Expo & React Native, featuring user authentication, product browsing, cart management, and user-specific favorites — all powered by AsyncStorage for local persistence.

🚀 Project Overview

This project is a complete frontend-based food delivery app designed for learning and demonstration purposes.
It simulates real-world food delivery app functionality such as:

User Registration & Login

Food Categories & Items

Add to Cart

Favorites (Wishlist)

User Profile

Persistent Data using AsyncStorage

The app is structured using Expo Router (file-based routing) for better scalability and clean navigation.

🧠 Key Features
👤 User Authentication

User Register & Login

User data stored locally using AsyncStorage

User-specific data handling (favorites)

🏠 Home Screen

Food categories:

🍕 Pizza

🍔 Burger

🍟 French Fries

🍗 Chicken

🌯 Rolls

🥤 Drinks

🥙 Kabab

Grid-based food item layout

Clean UI with images and prices

❤️ Favorites System

Add / Remove items from favorites

Favorites saved per user (email-based key)

Separate Favorites Screen

Auto refresh on screen focus

🛒 Cart System

Add items to cart

Quantity handling

Cart count badge

Cart data saved in AsyncStorage

👤 Profile Section

Displays logged-in user name

Optional profile image

Dynamic welcome message

🔄 Persistent Storage

Uses @react-native-async-storage/async-storage

Data remains saved even after app reload

🧩 Tech Stack
📱 Frontend

React Native

Expo

Expo Router (File-based routing)

🧠 State Management

React Hooks (useState, useEffect)

useIsFocused for screen refresh

💾 Local Storage

AsyncStorage

🎨 UI & Icons

@expo/vector-icons

Custom styling with StyleSheet
