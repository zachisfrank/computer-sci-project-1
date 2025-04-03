To ensure the program works as required, make sure all file paths are correct before using program

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
  
