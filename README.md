# Shopping List App

A simple and interactive shopping list application built with Flutter, designed to help you manage your grocery items effectively.

## Features

- **Add Items**: Add grocery items by entering the name, quantity, and selecting a category.
- **Remove Items**: Swipe to remove items from your shopping list.
- **Persistent Storage**: The app fetches and stores data in a Firebase Realtime Database, ensuring your list is saved even after closing the app.
- **Dark Theme**: The app uses a modern dark theme to reduce eye strain and save battery life on OLED screens.

## Getting Started

### Prerequisites

Ensure you have the following installed on your local development environment:

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Dart](https://dart.dev/get-dart)
- [Firebase Account](https://firebase.google.com/)

### Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Jalo1982/shopping_list_app.git
   cd shopping_list_app


### Folder Structure

```
lib/
│
├── data/
│   └── categories.dart          # Contains predefined categories
│
├── models/
│   ├── category.dart            # Defines the Category model
│   └── grocery_item.dart        # Defines the GroceryItem model
│
├── widgets/
│   ├── grocery_list.dart        # Main grocery list widget
│   └── new_item.dart            # Widget for adding new items
│
└── main.dart                    # Entry point of the application
```


### Code Overview

- **`main.dart`:** Initializes the application and sets up the theme.
- **`grocery_list.dart`:** A stateful widget that manages the list of grocery items. It fetches data from Firebase and allows the addition or removal of items.
- **`new_item.dart`:** Form for adding a new grocery item with validation.
- **`category.dart`:** Enum and model representing the different categories available.
- **`grocery_item.dart`:** Model representing an individual grocery item.

### Future Improvements

- **Edit Items:** Add functionality to edit existing items.
- **Remove Items:** Ability to remove items from the list.
- **User Authentication:** Implement user authentication to save the shopping list to the cloud.
- **Data Persistence:** Persist the grocery list locally using a database.

### Contributing

Contributions are welcome! Please open an issue or submit a pull request.
