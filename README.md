
# Library Management System 📚

This is a dynamic and fully functional **Library Management System** built using **ReactJS** for the frontend and **Node.js** with **MongoDB** for the backend. It supports user authentication, book management, and borrowing/returning functionalities.

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally:

### Step 1: Clone the Repository
1. Go to the repository: [Library Management System](https://github.com/Coder-Stark/Library_Management_System).
2. Click the green **Code** button and copy the HTTPS link.
3. Open your desired folder location, right-click, and open **Git Bash** or your terminal of choice.
4. Run the following command:
   ```bash
   git clone https://github.com/Coder-Stark/Library_Management_System.git
   ```

### Step 2: Setup the Backend
1. Navigate to the root directory where the `backend` and `frontend` folders are located.
2. Create a `.env` file in the backend directory (`backend/.env`) and add the following environment variables:
   ```env
   DB_URI=mongodb+srv://shivamkumar:lms@cluster0.x8a1c.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
   DB_NAME=lms
   SESSION_SECRET=mysecret
   ```
3. Open your terminal and navigate to the backend folder:
   ```bash
   cd backend
   ```
4. Install the backend dependencies:
   ```bash
   npm install
   ```
5. Start the backend server:
   ```bash
   npm start
   ```
   You should see the following message in the terminal:
   ```
   Server is listening on http://localhost:8080
   ```

### Step 3: Setup the Frontend
1. Open a new terminal and navigate to the frontend folder:
   ```bash
   cd frontend
   ```
2. Install the frontend dependencies:
   ```bash
   npm install
   ```
3. Start the frontend server:
   ```bash
   npm start
   ```
4. The project will open in your default browser.

---

## 🛠️ Features

1. **Dynamic Book Management**:
   - View the list of available books.
   - Add new books with details like name, ISBN, category, price, and quantity (Admin only).
   - Edit or delete books (Admin only).

2. **User Roles**:
   - **Guest**:
     - Borrow books (quantity decreases dynamically).
     - Return borrowed books (quantity increases dynamically).
   - **Admin**:
     - Manage books: Add, edit, and delete.

3. **Authentication**:
   - Predefined users:
     - **Guest**:
       - Username: `guest`
       - Password: `guest`
     - **Admin**:
       - Username: `admin`
       - Password: `admin`
   - Login required to borrow or manage books.

4. **MongoDB Integration**:
   - All data is stored in MongoDB Atlas, ensuring dynamic updates.

---

## 🖼️ Screenshots

### First Look of Site
![first look](https://github.com/Coder-Stark/Library_Management_System/blob/master/first%20look.png?raw=true)

### Login Screen
![Login Screen](https://github.com/Coder-Stark/Library_Management_System/blob/master/login%20screen.png?raw=true)

### Admin Panel
![Admin Panel](https://github.com/Coder-Stark/Library_Management_System/blob/master/admin%20panel.png?raw=true)

### Add a Book
![Add Book Screen](https://github.com/Coder-Stark/Library_Management_System/blob/master/add%20book.png?raw=true)

### Guest Panel
![Guest Panel](https://github.com/Coder-Stark/Library_Management_System/blob/master/guest%20panel.png?raw=true)

### Book Details (Borrow or Return)
![borrow or return](https://github.com/Coder-Stark/Library_Management_System/blob/master/borrow%20.png?raw=true)

### MongoDB Collections
![collections](https://github.com/Coder-Stark/Library_Management_System/blob/master/mongo%20DB%20collections.png?raw=true)

### Books DataBase
![books db](https://github.com/Coder-Stark/Library_Management_System/blob/master/books%20database.png?raw=true)

### Users DataBase
![users db](https://github.com/Coder-Stark/Library_Management_System/blob/master/users%20database.png?raw=true)


---

## 🤝 Contributions

Feel free to fork this repository and contribute to improving the system. Make sure to submit a pull request for any new features or fixes.

---