📚 Student Record Management System
A simple console-based C++ application that allows an admin to manage student records, including adding, viewing, updating, and deleting student data stored in a CSV file. The system includes basic authentication and a loading screen animation for better user experience.

🛠️ Features
🔐 Login System (Admin only)

➕ Add New Student Record

📄 View All Student Records

✏️ Update Existing Record

❌ Delete Record by Roll Number

💾 Data Stored in CSV File

📈 Console UI with ASCII Animation

🧑‍💻 Tech Stack
Language: C++

File Handling: fstream for reading/writing CSV

Console Effects: windows.h for loading animation and color

📂 File Structure
bash
Copy
Edit
├── main.cpp               # Entry point of the application
├── student.h              # Header file containing class/function declarations
├── student.csv            # CSV file to store student records (created at runtime)
🚀 How to Run
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/your-username/student-record-management.git
cd student-record-management
Compile the Code:

bash
Copy
Edit
g++ main.cpp -o student-management
Run the Application:

bash
Copy
Edit
./student-management
🔒 Note: Default login credentials are hardcoded. You can change them in the main.cpp file.
