# task6-
📚 SQL Task 6 — Online Bookstore Analysis with PostgreSQL
This project sets up a PostgreSQL database for an Online Bookstore, including schema creation, data import, and analytical queries. It simulates a real-world database scenario involving books, customers, and orders, and provides a foundation for running data analysis tasks.

📁 File Included
sql task 6.sql – Full SQL script to:

Create the database and tables

Import data

Run initial exploratory queries

🧰 Technologies Used
Database: PostgreSQL

Language: SQL (ANSI + PostgreSQL-specific commands)

⚙️ Requirements
PostgreSQL installed (v12+ recommended)

A SQL client like pgAdmin, DBeaver, or the psql terminal

Access to the data files used in COPY statements (adjust file paths as necessary)

🛠️ Setup & Usage
Open a PostgreSQL client and run the script sql task 6.sql.

Ensure you update the COPY file paths to match your local environment.

Review the sample queries at the end of the script to understand or expand upon the data.

🧾 Tables Created
Books

Book_ID, Title, Author, Genre, Published_Year, Price, Stock

Customers

Customer_ID, Name, Email, Phone, City, Country

Orders

Order_ID, Customer_ID, Book_ID, Order_Date, Quantity, Total_Amount

🔍 Sample Queries
The script includes initial SELECT * statements to display table contents after setup. You can extend it to include:

Top-selling books

Customer purchase history

Sales by genre or year

Inventory alerts for low stock

📌 Notes
Be sure to modify any COPY FROM paths (e.g., D:\Course Up\Data\books.csv) to valid paths on your system.

If running in a cloud environment or Docker, consider using \i or pg_restore for data import instead.

📄 License
For academic and personal use. Free to modify and extend
