### **Library Management System** 📚  

The **Library Management System** is designed to efficiently manage books, members, staff, and book borrowings using an **SQLite database** in **Google Colab**.  

#### **Key Functionalities**  

1. **Book Management** 📖  
   - Stores book details (Title, Author, Genre, Published Year, ISBN).  
   - Allows duplicate titles but ensures unique ISBNs.  

2. **Member Management** 👤  
   - Records member details (Name, Email, Phone, Registration Date).  
   - Handles missing data (some members may not have phone numbers or emails).  

3. **Borrowing System** 🔄  
   - Tracks book borrowings and due dates.  
   - Records return dates if available.  

4. **Staff Management** 👨‍💼  
   - Stores staff roles (Librarian, Assistant, Manager).  
   - Allows missing salary details for some records.  

5. **Data Handling** 📊  
   - Introduces **randomized** missing values & duplicate data.  
   - Optimized queries using **indexes** for efficient lookups.  

6. **Query Capabilities** 🔍  
   - Retrieve books, active members, and staff counts.  
   - Join operations to get borrowed book details with member names.  

This system ensures **efficient tracking** of library activities while simulating real-world **data inconsistencies**. 🚀