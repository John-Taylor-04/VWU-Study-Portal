# VWU-Study-Portal
A full-stack PHP and MySQL web application designed to connect students with tutors and study groups. The platform allows students to create tutoring requests, search for study groups, and manage tickets, while tutors can manage availability, subjects, and claim tutoring requests.


Features
    - Student Features
    - Create an account and log in
    - Submit tutoring requests
    - Select:
          - Subject
          - Days of the week
          - Available times
    - View submitted tutoring tickets
    - Search for study groups
    - Request group study sessions

Tutor Features
    - Register as a tutor
    - Create tutoring subject listings
    - Set tutoring availability
    - View open tutoring tickets
    - Claim tutoring requests
    - Manage assigned tutoring sessions
    
How It Works
1. Users create an account and choose whether they want to become a tutor.
2. Users log in using their generated ID and username.
3. Students submit tutoring requests based on:
    - Subject
    - Preferred days
    - Start/end times
4. Tutors set their:
    - Subjects
    - Availability
5. Tutors can view matching tutoring tickets and claim them.
6. Students can view assigned tutors and tutoring request status.
   
Security Features
    - Uses PHP sessions for authentication
    - Uses prepared SQL statements to reduce SQL injection risks
    - Session-based role handling for students and tutors
