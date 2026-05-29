Sison, CarlJusten Earl Domagas
API Call
This project is an API Call application using Postman that performs different types of requests such as GET, POST, PUT, PATCH, and DELETE for managing student information.
SETUP PROCEDURE Start by creating a Laravel project using the command: laravel new "project_name" in CMD.

After creating the project, open the terminal and create a model by using: php artisan make:model Student

Next, create the necessary migrations for the database tables: php artisan make:migration create_personal_access_tokens_table php artisan make:migration create_students_table

After that, configure the routes inside routes/api.php and create a controller named StudentsController inside the Http/Controllers folder.

Use php artisan tinker to create and manage the students table.

Open Postman and log in using a Gmail or GitHub account.

Create a new workspace and collection.

Inside the collection, create different API requests.

GET – Retrieves the student data in JSON format.

POST – Adds new student information such as name, course, and email.

PUT – Updates the selected student record by ID including the name, email, or course.

PATCH – Performs a partial update on a selected student record.

DELETE – Removes a student record by ID or deletes all student records.

And lastly, run the url using http://127.0.0.1:8000/api/students

LINK FOR THE VID OF API CALL BELOW: [https://drive.google.com/drive/folders/15ngUn6bDDfm_ybfFpLMxhY01-y1Pyxla?usp=sharing](https://drive.google.com/drive/folders/1KQ7sPXkuqa4Gl-GGeMgP1-YiGlq3Z_tI?usp=sharing)
