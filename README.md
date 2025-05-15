# 📚 Books Download Pllatform

A simple and efficient web application built with **Flask** and **MongoDB** to manage books in a personal or institutional library. This system allows users to perform URAD operations (Upload, Request, Approve and Delete) on books seamlessly through a web interface.

---

## 🚀 Features

- 📖 View all books)
- ➕ Add new books to the database
- ✏️ Edit and update book records
- 🗑️ Delete books from the system
- 💾 Data stored using MongoDB (NoSQL)
- 📥 Request and Download book from website after admin approval

---

## 🛠️ Technologies Used

- **Python 3**
- **Flask** - Web framework
- **MongoDB** - Database
- **PyMongo** - MongoDB driver for Python
- **HTML, CSS, Bootstrap** - Frontend

---

## 🧰 Installation and Setup

### 1. Clone the repository

```git clone https://github.com/net-cipher/books-management.git```
Extract the folder and open the VS Code editor and Open terminal

```cd books-management-system```

Create virtual environment

```python -m venv venv```

```venv\Scripts\activate```

```pip install -r requirements.txt```
Create an database named **storybook_platform** in your mongodb compass

Modify your mongodb url , example
```app.config["MONGO_URI"] = "mongodb://localhost:27017/storybook_platform"```

Run the Python program in Visual Studio Code terminal

i) start the main application
```python app.py```

ii) creating admin automatically through python code and saving it in database
```python create_admin.py```

iii)Adding books manually
```python add_books.py```

*remember*: Here, you should add your own book pdf to /static/books and its cover to /static/cover and rename which one you like and modify the "add_books.py" accordingly and run that python code(add_books.py) to add the book pdf which you have added inside /books folder.

Thank You! 
If any doubts, contact me through Instagram - www.instagram.com/cyber._.kiddie
