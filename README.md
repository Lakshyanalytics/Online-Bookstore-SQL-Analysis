# 📚 Online Bookstore SQL Analysis

This project simulates an online bookstore using PostgreSQL and CSV data files. It involves designing relational tables, importing datasets, and writing SQL queries (basic to intermediate) to extract valuable business insights related to customers, sales, inventory, and revenue.

---

## 🗃️ Dataset Structure

Three CSV files are used to represent the bookstore’s operational data:

- `Books.csv` – Book details (ID, title, author, genre, price, etc.)
- `Customers.csv` – Customer profiles (ID, name, email, location, etc.)
- `Orders.csv` – Sales transactions (date, quantity, total amount)

All files are available in the `/data` folder.

---

## ⚙️ Tools & Technologies

- **Database**: PostgreSQL  
- **Language**: SQL  
- **Data Source**: Custom-created CSV files  
- **IDE**: pgAdmin / DBeaver / VS Code

---

## 📌 Key Features

- ✅ Created relational database and normalized schema
- ✅ Imported structured data using the `COPY` command
- ✅ Executed 20+ queries ranging from simple filters to aggregate analysis
- ✅ Performed multi-table joins to generate business intelligence insights
- ✅ Tracked stock levels and revenue metrics post-order fulfillment

---

## 🔍 Query Highlights

> A full list of queries is available in [`Online_Bookstore_SQL_Project.sql`](Online_Bookstore_SQL_Project.sql)

Examples include:

- Retrieve all books in the "Fiction" genre  
- Calculate total revenue and remaining stock  
- Find the most frequently ordered book  
- List customers who spent more than $30  
- Rank top 3 expensive books in the Fantasy genre

---

## 🧪 How to Run This Project

1. Clone the repository  
2. Create a database in PostgreSQL (e.g., `OnlineBookstore`)  
3. Run the `Online_Bookstore_SQL_Project.sql` file  
4. Ensure CSV files are placed in a `/data` folder or update file paths in the SQL script

> 💡 *Note: This project was built using PostgreSQL. Some commands like `COPY`, `SERIAL`, and `\c` may not work in MySQL without modification.*

---

## 👨‍💻 Author

**Lakshya Rana**  
📬 [LinkedIn](https://www.linkedin.com/in/lakshya-rana-7b600a154/) | 🌐 [GitHub](https://github.com/Lakshyanalytics)  

---

## 📎 License

This project is open-source and free to use for educational and learning purposes.
