# Tulsi Mobile App - Technical Showcase

## Overview

Tulsi is a multi-platform mobile application designed to help users track their expenses in a simple, secure, and private manner. This repository serves as a showcase of the app's technical architecture, design patterns, and technologies used in its development. 

## Key Features (from a technical perspective)

* **Multi-Platform Development:** Built using Swift and Kotlin.
* **Local Data Storage:** Employs Core Data (iOS) and Room Persistence Library (Android) to ensure user data remains entirely on the device, addressing privacy concerns.
* **Clean Architecture:** Implements a layered architecture (MVP) to promote separation of concerns, maintainability, and testability.
* **Dependency Injection:** Uses dependency injection to manage dependencies.
* **Asynchronous Programming:** Uses async/await for asynchronous operations.
* **Unit Testing:** Includes a suite of unit tests to ensure the reliability and robustness of the application.

## Architecture

The app follows a Model-View-Presenter (MVP) architecture, with the following layers:

* **Models:** Defines the data structures for the application (e.g., Expense, Category).
* **Views:** Responsible for rendering the user interface. Built using SwiftUI (iOS) and Activities/Fragments (Android).
* **Presenters:** Handles user interactions and business logic, acting as an intermediary between the Views and the Interactors.
* **Interactors:** Contains the core business logic of the application, independent of any UI framework.
* **Repositories:** Manages data access, abstracting the underlying data source (e.g., local database).
* **Services:** Handles interactions with external services (e.g., database, APIs - for future extensions).
* **Utils:** Provides utility functions (e.g., date formatting, validation).

## Technical Highlights

* **Core Data (iOS):** Utilized for local data persistence, showcasing experience with managing structured data on iOS.
* **Room Persistence Library (Android):** Demonstrates knowledge of Android's recommended persistence library for storing structured data.
* **SwiftUI (iOS):** Built using SwiftUI, showcasing skills in modern UI development and reactive programming.
* **Kotlin (Android):** Developed using Kotlin, highlighting proficiency in a modern, concise, and powerful Android language.
* **MVP Pattern:** The adoption of MVP demonstrates an understanding of software architecture principles, promoting maintainability, testability, and separation of concerns.
* **Dependency Injection:** Improves code modularity and testability.
* **Unit Testing:** The presence of unit tests indicates a commitment to writing robust, reliable, and maintainable code.

## Future Considerations (for discussion)

* **Cloud Synchronization:** The app could be enhanced to support optional cloud synchronization, allowing users to access their data across multiple devices if users chose to do so.
* **Feature Enhancements:** Future features could include:
    * Budgeting and forecasting tools.
    * Integration with financial institutions.
    * Advanced reporting and analytics.
    * Montly report push notifications

## Conclusion

Tulsi aims to be a well-structured mobile application that aligns with mobile development best practices. The choice of native technologies, combined with a clean architecture and comprehensive testing, makes it a solid foundation for its sustainability in the future. 

## Pitch Deck
https://tulsi-expense-tracking-f-vdgrotl.gamma.site/

## Brand Guidelines
https://gamma.app/docs/Tulsi-Brand-Guidelines-Cultivating-Financial-Peace-of-Mind-1te25qa6xuth2a9
