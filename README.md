![WhatsApp Image 2025-09-13 at 16 39 35_d800b041](https://github.com/user-attachments/assets/217ca20d-b109-4738-b24a-5ec0bc908225)
![WhatsApp Image 2025-09-13 at 16 40 18_51358380](https://github.com/user-attachments/assets/9df27a58-833d-4ecb-8b1e-b05d05fa88b9)
![WhatsApp Image 2025-09-13 at 16 44 08_efab6939](https://github.com/user-attachments/assets/9d4ada10-5063-46d0-86c7-6627eac3af95)
![WhatsApp Image 2025-09-13 at 16 44 29_aacfb18a](https://github.com/user-attachments/assets/c0d7e589-2434-4f4a-9e59-af7550e055fc)


The following screenshots show the working of the Student CRUD REST API developed using Express + Mongoose and tested in Postman:

Create (POST /api/students)

Added a new student record with fields name, age, and major.

API responded with 201 Created and returned the saved student object with _id.

Read (GET /api/students)

Retrieved all students stored in the MongoDB collection.

API responded with 200 OK and returned an array of student objects.

Update (PUT /api/students/:id)

Updated an existing student’s details using their unique _id.

API responded with 200 OK and returned the updated student object.

Delete (DELETE /api/students/:id)

Deleted a student record from the database using _id.

API responded with 200 OK and returned a success message.
