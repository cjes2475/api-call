Sison, CarlJusten Earl Domagas
API Call

This project is an API Call application using Postman that performs different types of requests such as GET, POST, PUT, PATCH, and DELETE for managing student information.

## SETUP PROCEDURE 
1. Start by creating a Laravel project using the command: `laravel new "project_name"` in CMD.
2. After creating the project, open the terminal and create a model by using: `php artisan make:model Student`
3. Next, create the necessary migrations for the database tables: 
   * `php artisan make:migration create_personal_access_tokens_table`
   * `php artisan make:migration create_students_table`
4. After that, configure the routes inside `routes/api.php` and create a controller named `StudentsController` inside the `Http/Controllers` folder.
5. Use `php artisan tinker` to create and manage the students table.
6. Open Postman and log in using a Gmail or GitHub account.
7. Create a new workspace and collection.
8. Inside the collection, create different API requests:
   * **GET** – Retrieves the student data in JSON format.
   * **POST** – Adds new student information such as name, course, and email.
   * **PUT** – Updates the selected student record by ID including the name, email, or course.
   * **PATCH** – Performs a partial update on a selected student record.
   * **DELETE** – Removes a student record by ID or deletes all student records.
9. And lastly, run the url using `http://127.0.0.1:8000/api/students`

### VIDEO LINK
[View API Call Video](https://drive.google.com/drive/folders/1KQ7sPXkuqa4Gl-GGeMgP1-YiGlq3Z_tI?usp=sharing)