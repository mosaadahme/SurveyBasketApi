Survey Basket API
Survey Basket API is a robust API built with .NET Core to manage surveys, votes, and results. It is designed to be efficient, scalable, and easy to use, with features that enhance the user experience and system performance.

Features
1. Error Handling
The API catches and handles errors in a structured way. If something goes wrong, the system returns a clear and understandable error message.

2. Exception Handling
Custom exceptions are used to handle specific errors. This helps the system manage unexpected issues and provide accurate error messages.

3. Logging
Important actions (like requests and errors) are logged, so the system can be monitored and issues can be found and fixed quickly.

4. Caching
The API uses Redis to store frequently accessed data temporarily, speeding up the system by reducing database queries.

5. Background Jobs
Time-consuming tasks (like sending emails) run in the background, keeping the API responsive and fast for users.

6. Roles & Permissions
The API ensures that only authorized users can perform certain actions. Admin users have more control, while regular users can vote and view surveys.

7. Pagination, Filtering, and Sorting
Pagination: Breaks data into smaller chunks, making it easier to load.
Filtering: Users can filter data by different criteria (e.g., active surveys).
Sorting: Allows sorting of data by specific fields (e.g., by date or name).
8. Health Check
The system has a health check feature to monitor if everything is working properly. This helps keep the system running smoothly.

9. Rate Limiting
The API limits how many requests a user can make in a short period. This helps protect the system from being overloaded by too many requests.

10. API Versioning
Supports multiple versions of the API, so older versions continue to work even after updates. This makes it easier to maintain backward compatibility.

11. Swagger/OpenAPI
Swagger provides interactive documentation where developers can see and test all the available endpoints, making it easier to understand how the API works.
