# Task Management Application

## Overview

A dynamic, responsive web-based task management application developed during my internship at **EcodeCamp**. This app allows users to manage tasks effectively with features like adding, editing, completing, and removing tasks. It also includes the capability to download task details as a Word document.


![a1](https://github.com/user-attachments/assets/1e21e438-a793-4f2b-9a0e-e3f9283ffc0a)
![2](https://github.com/user-attachments/assets/d7b269fb-d624-47ef-8726-6c34d9b32a29)
![3](https://github.com/user-attachments/assets/f101f526-317c-4b18-b613-abb39f355612)
![4](https://github.com/user-attachments/assets/bee4231c-d886-446a-bac3-e23acd876989)



## Key Features
- Add, edit, complete, and remove tasks
- Download task details as a Word document
- Responsive design for seamless use across devices
- Real-time updates for task status

## Tech Stack
- **Backend**: Python with Flask & SQLite
- **Frontend**: HTML5, CSS3, Bootstrap
- **Database**: SQLAlchemy with SQLite
- **Document Handling**: Python-docx for generating Word files
- **Version Control**: Git & GitHub

## Installation

1. Clone the repository:
    git clone https://github.com/engrmumtazali0112/todo_lista_app

2. Navigate to the project directory:
    cd task-management-app

3. Create a virtual environment:
    python -m venv venv

4. Activate the virtual environment:
    - On Windows:
      venv\Scripts\activate

5. Install the dependencies:
    pip install -r requirements.txt
  

6. Set up the database:
    flask db upgrade
  

7. Run the application:
    flask run


## Contributing

Feel free to fork the repository and submit pull requests. For any issues or suggestions, please open an issue on GitHub.

## License

This project is licensed under the MIT License.

## Contact

For any inquiries or collaboration opportunities, you can reach me at engrmumtazali01@gmail.com

requirements.txt
This file lists the project dependencies. Create this file with the following content:
makefile
Copy code
Flask==2.0.3
Flask-SQLAlchemy==2.5.1
Flask-Migrate==3.1.0
python-docx==0.8.11
setup.md
This file describes the environment setup. Here’s an example:
markdown

# Environment Setup

## Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

## Steps to Set Up

1. **Clone the Repository**
   git clone https://github.com/engrmumtazali0112/todo_lista_app
   cd task-management-app
2.	Create and Activate a Virtual Environment
o	On Windows:
python -m venv venv
venv\Scripts\activate

python -m venv venv
source venv/bin/activate

3.	Install Dependencies
pip install -r requirements.txt

4.	Initialize the Database
flask db upgrade

5.	Run the Application
flask run

6.	Access the Application Open your web browser and go to http://127.0.0.1:5000.
Additional Notes
•	Ensure you have the necessary permissions to execute these commands.
•	For any issues or queries, please check the README.md or contact the repository maintainer.
sql


### **3. Add Files to the Repository**

1. **Navigate to the Local Repository Directory**: If not already there, use your terminal or command prompt to navigate to the directory where you cloned the repository.

2. **Add and Commit Files**:
   git add README.md requirements.txt setup.md
   git commit -m "Initial commit with README, requirements, and setup files"
   
4.	Push to GitHub:
git push origin main
Replace main with the default branch name if it’s different.

## Contact
Made with ❤️ by Mumtaz Ali | [LinkedIn](https://www.linkedin.com/in/mumtaz-ali) | [GitHub](https://github.com/engrmumtazali0112)
<div align="center">
<h3> Connect with me
</h3> 
<p align="center">
    <a href="mailto:engrmumtazali01@gmail.com" target="_blank"><img alt="Gmail" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Gmail.svg"></a> 
    <a href="https://www.linkedin.com/in/mumtazali12/" target="_blank"><img alt="LinkedIn" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Linkedin.svg"></a>
    <a href="https://www.instagram.com/its_maliyzi?igsh=MWR1Y2x1a2xpazBpOA==" target="_blank"><img alt="Instagram" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Instagram.svg"></a>
    <a href="https://www.hackerrank.com/profile/engrmumtazali01" target="_blank"><img alt="HackerRank" width="25px" src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/HackerRank.svg"></a>
    <a href="https://github.com/engrmumtazali0112" target="_blank"><img src="https://cdn.svgporn.com/logos/github-icon.svg" alt="Github logo" width="25px"></a>
</p>  

