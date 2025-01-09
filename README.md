
Part of the Web Application for Student Courses:

This service is responsible for routing traffic to individual services.

Examples of use:

LOGIN: http://localhost:9000/student-service/auth/authenticate
REGISTRATION: http://localhost:9000/student-service/auth/register
GET COURSES: http://localhost:9000/course-service/courses
Thanks to the gateway, we can invoke endpoints using the service name.
