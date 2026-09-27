# Mobile Shop CRUD Project

A command-line Python application that implements a complete CRUD (Create, Read, Update, Delete) system for a mobile shop's inventory management[cite: 1]. The application stores data temporarily in-memory using a global Python list[cite: 1].

## Features

*   **Add Mobile:** Insert a new mobile record into the inventory[cite: 1].
*   **Display All Mobiles:** View a cleanly formatted table of all available mobile records[cite: 1].
*   **Search Mobile:** Locate and view a specific mobile's details using its unique ID[cite: 1].
*   **Update Mobile:** Modify the brand, model, price, and quantity of an existing mobile[cite: 1].
*   **Delete Mobile:** Remove a mobile record entirely from the list[cite: 1].

## Technologies Used

*   **Language:** Python
*   **Version:** Python 3.10+ (Required for the `match-case` statement used in the main dashboard)[cite: 1].
*   **Storage:** Built-in Python lists (In-memory storage)[cite: 1].

## Internal Data Structure

Each mobile is stored as a simple list containing five elements in a strict order: `[id, brand, model, price, quantity]`[cite: 1]. 
Example record: `[101, "Samsung", "Galaxy A55", 35000, 5]`[cite: 1].

## Project Structure

The codebase is divided into two modules for better organization:
*   `operations.py`: Contains the global `mobiles` list and all the functional logic (Create, Read, Update, Delete) required to manipulate the data.
*   `main.py`: Contains the `dashboard()` while-loop menu and serves as the main entry point to run the application[cite: 1].

## How to Run

1.  Ensure you have Python 3.10 or newer installed on your system.
2.  Clone this repository or download both `main.py` and `operations.py` into the same folder.
3.  Open your terminal or command prompt.
4.  Navigate to the folder containing the project files.
5.  Execute the application by running:

```bash
python main.py
