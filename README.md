# Global Superstore

Welcome to Global Superstore, a project aimed at managing the operations of a global retail superstore. This project provides a service layer to handle various store operations efficiently.

## Project Overview

The Global Superstore project encompasses the following components:

- **Controller**: Handles incoming requests and delegates them to the service layer.
- **Service**: Contains business logic for managing store operations such as adding, updating, and retrieving items.
- **Repository**: Interfaces with the database to perform CRUD operations on store items.
- **Constants**: Defines constants used throughout the project.
- **Item**: Represents an item in the store, containing attributes such as ID, name, price, and date.
- **Application**: Main entry point for the application.

## Service Layer

### StoreService

The `StoreService` class provides methods for interacting with store items:

- **getItem(int index)**: Retrieves an item from the store by index.
- **addItem(Item item)**: Adds a new item to the store.
- **updateItem(Item item, int index)**: Updates an existing item in the store.
- **getItems()**: Retrieves all items from the store.
- **getItemfromId(String id)**: Retrieves an item from the store by ID.
- **getIndexFromId(String id)**: Retrieves the index of an item by ID.
- **within5Days(Date newDate, Date oldDate)**: Checks if a given date is within 5 days of another date.
- **handleSubmit(Item item)**: Handles the submission of a new or updated item, ensuring it meets certain criteria.

## Getting Started

To set up and run the Global Superstore project:

1. Clone the repository: `git clone https://github.com/yourusername/Global-Superstore.git`
2. Ensure you have Java and Spring Boot installed on your machine.
3. Run the application using your preferred IDE or the command line.

## Usage

Once the application is running, you can interact with it through RESTful endpoints. Use tools like Postman or cURL to make requests to the controller endpoints.

## Contributing

Contributions to the Global Superstore project are welcome! Whether you want to add new features, fix bugs, or improve documentation, feel free to open issues or submit pull requests.

## Acknowledgments

We extend our appreciation to all contributors and users of the Global Superstore project. Your support and feedback are invaluable in making this project successful.
