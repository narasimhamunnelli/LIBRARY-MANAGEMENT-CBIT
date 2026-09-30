# 📚 Library Management System

A **web-based Library Management System** developed to automate and simplify the day-to-day operations of a library. The application provides an easy-to-use interface for managing books, checking availability, issuing books, and returning books.

The project is developed using **Python and Flask** for the backend, with **HTML and CSS** for the frontend.

## 🚀 Features

* 📖 Add and manage books
* 🔍 Search books by:

  * Book ID
  * Title
  * Author
* ✅ Check book availability
* 📤 Issue books to users
* 📥 Return issued books
* 👨‍💼 Librarian login
* 📋 View list of available and issued books
* 💾 Store and manage library records
* 🖥️ Simple and user-friendly web interface

## 🛠️ Technologies Used

### Backend

* **Python**
* **Flask**

### Frontend

* **HTML5**
* **CSS3**

### Data Management

* **Excel**
* **Pandas**
* **OpenPyXL**

## 📂 Project Structure

```text
LIBRARY-MANAGEMENT-CBIT/
│
├── app.py
├── books.xlsx
├── requirements.txt
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── add_book.html
│   ├── issue_book.html
│   ├── return_book.html
│   └── books.html
│
├── static/
│   └── style.css
│
└── README.md
```

> The exact files may vary depending on the current version of the project.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/narasimhamunnelli/LIBRARY-MANAGEMENT-CBIT.git
```

### 2. Navigate to the project folder

```bash
cd LIBRARY-MANAGEMENT-CBIT
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install required packages

```bash
pip install flask pandas openpyxl
```

Or, if `requirements.txt` is available:

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

### 7. Open in browser

Go to:

```text
http://127.0.0.1:5000/
```

## 🔄 How the System Works

```text
User
  ↓
Web Interface
  ↓
Flask Application
  ↓
Book Management
  ↓
Excel Database
  ↓
Book Availability / Issue / Return
```

### Book Management

The librarian can add new books and maintain existing book information such as:

* Book ID
* Book Title
* Author
* Availability

### Search

Users can search for books using the **Book ID, Title, or Author**.

### Issue Book

When a book is issued, the system updates its availability status.

```text
Available → Issued
```

### Return Book

When a book is returned, its availability is updated.

```text
Issued → Available
```

## 📊 Data Storage

The project uses an Excel file (`books.xlsx`) for storing book information.

**Pandas** is used for data processing, while **OpenPyXL** is used to read and write Excel files.

Example:

| Book ID | Title               | Author           | Status    |
| ------- | ------------------- | ---------------- | --------- |
| B001    | Python Programming  | John Smith       | Available |
| B002    | Digital Electronics | Thomas Floyd     | Issued    |
| B003    | Computer Networks   | Andrew Tanenbaum | Available |

## 🎯 Project Objectives

* Automate basic library operations.
* Reduce manual record maintenance.
* Provide quick book searching.
* Track book issue and return status.
* Create a simple web-based library management solution.
* Gain practical experience in **Python, Flask, HTML, CSS, Pandas, and Excel data handling**.

## 🔮 Future Enhancements

The project can be further improved by adding:

* 👤 Student/user registration
* 🔐 Secure authentication
* 🗄️ MySQL or SQLite database
* 📧 Email notifications
* 📅 Due-date tracking
* 💰 Fine calculation
* 📊 Admin dashboard
* 📱 Responsive mobile interface
* ☁️ Cloud deployment

## 👨‍💻 Author

**Narasimha Munnelli**

Electronics and Communication Engineering Student

GitHub:
https://github.com/narasimhamunnelli

## 📜 License

This project is developed for **educational and academic purposes**.
