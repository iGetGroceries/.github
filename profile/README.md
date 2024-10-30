# iGetGroceries Organization
Aisle say, shopping just got fun. Grocery bliss in a click. Taking the guesswork out of grocery shopping and recipe planning.

### Organize your grocery list, streamline your shopping. Simple, efficient, and tailored for every user.

Welcome to the **iGetGroceries** GitHub organization, where you'll find the modular components that power the **iGetGroceries** app—a grocery list manager designed to help users organize, categorize, and track their grocery items with ease. As the sole developer, I’ve structured this organization to demonstrate my commitment to modularity, maintainability, and the overall quality of iOS development.

## Organization Overview

**iGetGroceries** goes beyond a typical grocery list app by offering flexible item management and category customization, all built on a foundation of modular, reusable code. By breaking down the main features of the **iGetGroceries** app into independent Swift packages, I’m showcasing my dedication to clean architecture, readable code, and efficient design for long-term maintainability.

## Public Repositories

### 1. [iGetGroceriesGroceryItems](https://github.com/iGetGroceries/iGetGroceriesGroceryItems)
The `iGetGroceriesGroceryItems` package provides core functionality for managing grocery items and their categories within the **iGetGroceries** app. Users can define grocery items with properties like name, category, purchase status, and associated markets. This module supports user permissions, such as limiting item additions for guest users, and includes a comprehensive set of SwiftUI views and modifiers to enable a user-friendly experience.

### 2. [iGetGroceriesSharedUI](https://github.com/iGetGroceries/iGetGroceriesSharedUI)
The `iGetGroceriesSharedUI` package encapsulates shared UI elements and utilities used across the **iGetGroceries** app. This module includes the `CategoryColor` utility for managing category colors and view extensions for customizing segmented pickers. By centralizing UI elements, `iGetGroceriesSharedUI` ensures a cohesive look and feel across the app while also simplifying the development of new UI components.

## Development Philosophy

The **iGetGroceries** organization is guided by key development principles:

- **Modularity:** Each feature is isolated in its own Swift package, allowing for easy updates, testing, and reusability across projects.
- **Readability:** Writing clean, easy-to-read code is essential, making the codebase approachable and maintainable over time.
- **Maintainability:** The modular architecture enables isolated changes, ensuring updates can be made without impacting unrelated components.
- **Testing:** While public packages are focused on core functionality, the **iGetGroceries** app prioritizes comprehensive testing to maintain a reliable user experience.
- **Architecture:** Leveraging Swift package modularity keeps features decoupled, allowing each component to evolve independently. This structure simplifies updates and reduces the risk of regressions.

## Contribution Guidelines

While active collaboration is not currently sought, feature requests, issues, and discussions are welcome. The public repositories are open for exploration, and contributions that align with the project’s goals and principles are encouraged.

---

The **iGetGroceries** organization offers a glimpse into best practices for Swift development and modular architecture, showcasing an efficient, organized approach to building an iOS grocery list manager.
