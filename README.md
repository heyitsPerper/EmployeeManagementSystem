Employee Management System

Used to develop: Laravel, Composer, Git Bash, Xampp, VSCode, Bootstrap, Browser

HOW TO RUN EMPLOYEE MANAGEMENT SYSTEM:
1. Clone the system from github by typing "git clone -b master --single-branch https://github.com/heyitsPerper/EmployeeManagementSystem.git" in git bash
2. Make sure to place the cloned system inside C:\xampp\htdocs
3. Open MySQL Admin in the browser and create a database named "records_db"
4. Open vscode then open the EmployeeManagementSystem folder
5. Type in the vscode terminal: 
    composer install
    php artisan key:generate
    php artisan migrate
    php artisan serve
6. Open browser then copy paste this link http://localhost:8000/EmployeeManagementSystem/admin/login

LOGIN CREDENTIALS:
Username: girlgroup
Password: 1111

Features of this system:
Admin Login
Manage employee's record (CRUD)
Manage departments (CRUD)
Displays numbers of registered employee and its sessions

Developers:
Ferlyn P. Ruiz
Asiley A. Pepe
Marilou Y. Rubio
Maria Ellaine P. Perez
Emilyn Ranollo
