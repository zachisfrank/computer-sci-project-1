To ensure the program works as required, make sure all file paths are correct before using program
The admin username: admin
The admin password: admin
click on consolidated.py to start the program
# Project Description

This project involves developing a Python-based software solution for a small family business that sells games. The software aims to streamline the management of customer orders, inventory, and sales records while ensuring data security and accuracy. A simple text-based interface will be used to interact with the system, allowing for efficient operation without requiring advanced technical knowledge.

The solution will include features to accept customer orders, check game availability, manage stock levels, and generate reports on sales activity, such as a full list of orders in the last month.
![image](https://github.com/user-attachments/assets/e5a11b55-bc0c-49d3-bcb7-d640a74a566d)
# Problem Outline

  The software solution must includes an effective way to manage customers information securely and record the sales information for the business that “A family member” has started by selling games. This includes managing inventory, tracking sales, updating stock and managing game data info.
    
   ### Objectives
  - **Customer Information Management:**
     - Implement a secure system to store and manage customer information, including names, contact details, and purchase history.
  - **Sales Recording:**
     - Record all sales transactions, linking them to customer profiles for accurate tracking and analysis.
  - **Inventory Management:**
     - Maintain an up-to-date record of game stock, ensuring inventory levels are adjusted automatically after each sale.
  - **Game Data Management:**
     - Provide a structured system to store and retrieve game details, including titles, prices, genres, and stock quantities.
  - **Data Security:**
     - Protect customer and sales data using restricted access, ensuring the business complies with basic security standards.
  - **Simple User Interface:**
     - Design an easy-to-use command-line interface to browse games, manage inventory, and process sales efficiently.

# Requirement List

### Requirements for the Solution:

1. **Core Functionalities**
    - **Order Management:**
        - Accept customer orders and process them efficiently.
        - Check the availability of games in stock before confirming orders.
    - **Inventory Management:**
        - Update stock levels automatically after each sale.
    - **Sales Recording:**
        - Record each transaction with details such as customer information, date, and total sale amount.
        - Generate reports for sales.
2. **Customer Data Management**
    - Store customer information securely, and purchase history.
3. **User Interface**
    - Provide a simple text-based interface for:
        - Viewing game catalogs.
        - Placing and managing orders.
        - Generating sales and inventory reports.
4. **Programming Features**
    - Use file storage (e.g., CSV, JSON. TXT) or a lightweight database (e.g., SQLite) to manage data.
    - Implement error handling to prevent system crashes from invalid inputs or missing data.
5. **Security**
    - Restrict access to the software’s administrative functionalities.

# Ethical/Legal/Security Concerns

### Ethical and Legal Issues:

1. **Data Privacy:**
    - Customer information must be stored securely to comply with data protection laws.
2. **Data Security:**
    - Implement encryption or password protection to safeguard sensitive data from unauthorized access.
    - Regularly update and back up data to prevent loss due to system failures.
3. **Ethical Sales Practices:**
    - Ensure that the software does not encourage overselling or misleading inventory status (e.g., claiming items are in stock when they are not).

# Data Quality

### Factors Affecting Data Quality:

1. **Accuracy:**
    - Input errors, such as misspelled customer names or incorrect order details, can lead to inaccurate records. Implement validation checks to reduce this risk.
2. **Consistency:**
    - Ensure that inventory updates, sales records, and customer information remain consistent across the system.
3. **Timeliness:**
    - Regular updates to inventory and sales data are critical to ensure accurate information is available at all times.
4. **Completeness:**
    - Missing or incomplete customer or sales data can impact reporting and analysis. Add mandatory fields to prevent incomplete entries.
5. **Storage Limitations:**
    - Use a structured data storage approach (e.g., relational databases) to prevent data corruption or loss.
   
# **Evidence of testing**

  - There is already live test data within the users.txt file and game_list.txt file this all works well, 
    although i had to change the delimitation within the user file for how i stored time values from '.' to ' ' because the time values were stored as floats which would incorrectly read the values.

| Test Case | Input | Expected Output |
| --- | --- | --- |
| Register a new user | New username & password | User is added to file, login is possible afterward |
| User login with correct credentials | Existing username/password | Access granted |
| View balance | User selects 'a' from menu | Current balance printed |
| Purchase a game with sufficient funds | Valid game key & balance | Game added to orders, balance deducted, confirmation |
| Withdraw more than available balance | Balance: $10, Withdraw: $50 | "Insufficient funds" |

## **Design Validation**

### Reflection Checklist:

-  Game delivery works using timestamp difference
-  Orders are tracked per user
-  File reading and writing persists data accurately
-  Admin access and user access are separate
-  Dictionary usage ensures O(1) search time
-  Modularity effectively used to make the program well encapsulated
-  The logistical side of reading and using the values found within dictionaries was implemented easily
-  Reading and Writing from text files required tons of testing and debugging
-  I wish to implement a better form of admin that lets you manipulate more date easier
-  A possible limitation could include the fact you must wait 5 days for programs to be in your library
-  I wish to also use a gui next time but found that learning and implementing effectively takes too long

### Source of information
- Information includes some advice from AI chatbot ChatGPT and Sometimes Integrated AI data scrapers within google searches
- https://www.w3schools.com/python/gloss_python_remove_dictionary_items.asp
- https://www.bing.com/search?pglt=417&q=python+delimiter+for+dictionary&cvid=4d061757c7bf4b6085197a289da9f20b&gs_lcrp=EgRlZGdlKgYIABBFGDkyBggAEEUYOTIGCAEQABhAMgYIAhAAGEAyBggDEAAYQDIGCAQQABhAMgYIBRAAGEAyBggGEAAYQDIGCAcQABhAMgYICBAAGEDSAQg3NjU1ajBqMagCALACAA&FORM=ANNTA1&PC=LCTS
- https://www.epochconverter.com/
- https://www.geeksforgeeks.org/python-time-module/
- https://stackoverflow.com/questions/7370801/how-do-i-measure-elapsed-time-in-python
- https://github.com/microsoft/pylance-release/issues/4359
- https://stackoverflow.com/questions/6161799/append-list-within-classes-python
- https://stackoverflow.com/questions/19596750/is-there-a-way-to-clear-your-printed-text-in-python
- https://www.geeksforgeeks.org/sort-in-python/
- https://www.geeksforgeeks.org/how-to-read-from-a-file-in-python/#linebyline-reading-in-python
- https://stackoverflow.com/questions/40375790/how-to-call-a-function-within-a-nested-class
