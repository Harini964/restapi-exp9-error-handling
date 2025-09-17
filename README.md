![WhatsApp Image 2025-09-13 at 16 54 06_ce0c86cc](https://github.com/user-attachments/assets/a12b54cf-fa8b-4d1c-b0ad-6f4a52d27db3)



The screenshot below demonstrates the error handling implemented in the Student REST API.
Here, a GET request was made to fetch a student by ID using an invalid MongoDB ObjectId format.

As designed, the API correctly responds with a 400 Bad Request status and returns a clear error message:

{
  "error": "Invalid ID format."
}


This ensures that users and developers can easily identify mistakes in their requests and handle them appropriately.
