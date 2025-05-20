## 🏠 AirbnbUI - SwiftUI Clone

A fully-functional Airbnb UI clone built entirely with SwiftUI. This project demonstrates modern iOS app architecture, MVVM design patterns, and SwiftUI best practices without relying on Firebase or other backend services.


![Screenshot 2025-05-19 at 4 19 56 PM](https://github.com/user-attachments/assets/8faf2d02-7ff7-4095-af45-1d74be17c64e)

![Screenshot 2025-05-19 at 4 20 14 PM](https://github.com/user-attachments/assets/e69d8b48-c7c9-4128-9301-d3933fd59a6c)



## ✨ Features

Authentic Airbnb Experience: Pixel-perfect UI replication of the Airbnb iOS app
Complete User Flows: Explore listings, view details, search locations, and toggle map view
Authentication System: Full login and registration screens with validation
MVVM Architecture: Clean separation of business logic and presentation
Mock Services: Authentication and data services for testing without a real backend
Location Integration: Map views and location services using MapKit
SwiftUI Showcase: Demonstrates advanced SwiftUI concepts including:

TabViews, NavigationStack, and Sheet presentations
Custom ViewModifiers for consistent UI components
ObservableObject and state management
Async/await for API calls
Protocol-oriented programming



## 📱 Screens

- Explore View with listings
- Listing Detail View
- Map View with interactive pins
- Search and Filtering
- Authentication (Login/Register)
- User Profile
- Wishlists

## 🏗️ Architecture

This project follows the MVVM (Model-View-ViewModel) pattern:
- Models: Data structures like Listing
- Views: SwiftUI views
- ViewModels: Business logic and state management
- Services: Mock data and authentication providers
- Protocols: Interface abstractions for services

File description based on the structure: [Mock_Airbnb.pdf](https://github.com/user-attachments/files/20319996/swift.pdf)


## 🛠️ Technical Highlights

Protocol-based Authentication: Flexible auth system that can easily switch between mock and real implementations
Lazy Loading: Efficient list rendering with LazyVStack
Custom Components: Reusable UI elements like ListingImageCarouselView and CircularProfileImageView
Robust ViewModels: Handles network requests and business logic

## System Design
<img width="1233" alt="Screenshot 2025-05-19 at 5 54 08 PM" src="https://github.com/user-attachments/assets/b58955e8-236c-4300-bd61-483c1bf304e8" />

