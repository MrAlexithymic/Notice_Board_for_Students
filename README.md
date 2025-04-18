# Notice_Board_for_Students
# 📘 Student View - Online College Notice Board

This is the **Student View** module of the **Online College Notice Board** web application. It allows students to view and search for college notices uploaded by the admin. Notices may include attachments such as PDFs, images, or documents.

## 🚀 Features

- View all notices with title, content, and timestamp.
- Preview or download attached files (PDF, image, DOCX, etc.).
- Search notices by title or content.
- Responsive and simple UI for easy access.

## 🛠️ Technologies Used

- Python (Flask)
- MySQL
- HTML/CSS
- Jinja2 Templates

## 📁 Folder Structure
Student_view_page/ ├── init.py ├── students_view.py # Flask routes for student notice view ├── templates/ │ └── index.html # Frontend for students └── static/ ├── css/ │ └── style.css # Styling (if applicable) └── uploads/ # Folder for downloaded/viewed attachments


## 🧰 Setup Instructions

1. Clone the repository or copy this module inside your main Flask project.
2. Make sure your MySQL server is running and the `college_notices` database is set up.
3. Update your database credentials in `students_view.py`.
4. Install dependencies (see `requirements.txt` below).
5. Run the student server:
   ```bash
   python students_view.py
6. Visit http://localhost:5000 to see the student view.

📦 Requirements
Install with:
pip install flask mysql-connector-python

Or use the requirements.txt:
Flask
mysql-connector-python

📝 License
This project is part of a college academic project and open for educational use.
