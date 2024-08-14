# Shopping List App

A simple, intuitive Flutter application for managing your grocery shopping list. The app allows users to add items to their grocery list, categorize them, and keep track of quantities.

## Features

- **Add Grocery Items:** Add new items to your shopping list with name, category, and quantity.
- **Categorization:** Items are categorized into predefined categories like Vegetables, Fruits, Meat, Dairy, and more.
- **Dark Theme:** The app comes with a sleek dark theme for a better user experience.
- **Validation:** Ensures that the item name and quantity are valid before adding them to the list.

## Getting Started

### Prerequisites

- Flutter SDK
- Dart SDK

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Jalo1982/shopping_list.git
    cd shopping_list
    ```

2. **Install dependencies:**
    ```bash
    flutter pub get
    ```

3. **Run the app:**
    ```bash
    flutter run
    ```

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
- **`grocery_list.dart`:** Displays the list of grocery items and handles adding new items.
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
