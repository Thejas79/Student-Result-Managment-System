# Student-Result-Managment-System
This is a Student Result Management System developed using Java (Swing GUI) and MySQL. The system allows administrators to add students, enter their results, and view academic records in a structured format.

📦 What's Inside?
After unzipping the project, you’ll find:

graphql
Copy
Edit
Student Result Management System/
├── src/                           # Java source code files
│   ├── AdminHome.java
│   ├── AddResult.java
│   ├── AddStudent.java
│   ├── StudentHome.java
│   └── ... (other GUI and logic files)
├── sql/
│   └── student.sql               # SQL script to create and populate DB
├── README.md                     # Project instructions
├── lib/                          # Any external JARs if provided
└── ... (config files or resources)
🛠 Requirements
Java JDK 8 or later

MySQL Server (XAMPP/WAMP or standalone)

Any IDE (IntelliJ, Eclipse, NetBeans)

🚀 How to Run the Project
🗂 Step 1: Import Project
Unzip the project folder.

Open it using your Java IDE (e.g., IntelliJ, Eclipse).

Make sure src/ is set as a source folder.

🧱 Step 2: Set Up Database
Open phpMyAdmin or your preferred MySQL client.

Create a new database, e.g., srm.

Import the SQL file:

Locate student.sql in the sql/ folder.

Run the script to create tables and populate default data.

⚙️ Step 3: Configure DB Connection
Open the database connection code file (e.g., ConnectionProvider.java).

Update:

java
Copy
Edit
String url = "jdbc:mysql://localhost:3306/srm";
String user = "root";
String password = ""; // Update if you have a password
▶️ Step 4: Run the Application
Run AdminHome.java to open the admin dashboard.

Run StudentHome.java to allow student access to view results.

✨ Features
Admin login panel

Add new students

Enter marks for students

View student result

Search and filter students

Friendly GUI using Java Swing

🧠 Modules Overview
Admin Panel

Add Student

Add Result

View Registered Students

View All Student Results

Student Panel

Enter Roll Number to view results

📌 Notes
Ensure MySQL server is running before launching the app.

Tables like student and result must exist in the database.

You can customize grades, departments, and subjects in the database.

//***all files here are uploaded seperately so combine all and put them in a file***\\
