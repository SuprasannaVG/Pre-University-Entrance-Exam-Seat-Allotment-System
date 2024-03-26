# Pre-University-Entrance-Exam-Seat-Allotment-System
# Skills: SQL , Python, PHP, HTML-CSS

# Introduction:
The Pre-University Entrance Exam Seat Allotment System is a comprehensive platform designed to efficiently allocate available seats across various streams—Science, Commerce, Arts, and Diploma—based on students' entrance exam results. With limited seats available for each stream, this system prioritizes the allocation process by initially assigning seats to the least-ranked students, ensuring fair distribution and optimal utilization of resources. Leveraging a combination of SQL for database management and Python, PHP, and HTML-CSS for web development, this system streamlines the seat allotment process, providing a transparent and accessible interface for students, administrators, and stakeholders involved in the pre-university education system.

# Implementation:

1. **Database Creation**:
    - **Register Table**: This table stores information about registered users, including unique user IDs, usernames, email addresses, passwords, and registration timestamps.
    - **Login Table**: This table holds login credentials for users, linking them to their respective registered accounts.
    - **Student Details Table**: This table contains detailed information about students, such as student ID, name, address, contact information, and any other relevant personal details.
    - **Course Details Table**: This table stores information about available courses, including course IDs, course names, descriptions, duration, and any prerequisites.
    - **Result Table**: This table stores the results of the entrance exam or any other relevant assessments, linking student IDs to their respective scores or ranks.

2. **User Interface Webpages**:
    - **Register Page**: This webpage allows new users to create an account by providing necessary details such as username, email, and password. Upon submission, the information is stored in the Register table.
    - **Login Page**: This webpage enables registered users to log in by entering their credentials. Upon successful authentication, users are redirected to their respective dashboards.
    - **Student Details Page**: This webpage displays and allows users to manage their personal information stored in the Student Details table. Users can update their details as necessary.
    - **Course Details Page**: This webpage provides information about available courses, including descriptions, durations, and prerequisites, retrieved from the Course Details table.
    - **Result Page**: This webpage displays the results of the entrance exam or assessments stored in the Result table. Users can view their scores or ranks.

3. **Backend Implementation**:
    - The backend logic is implemented using Python and PHP for database interaction, user authentication, and data retrieval.
    - SQL queries are utilized to perform CRUD operations (Create, Read, Update, Delete) on the database tables.
    - Authentication mechanisms are implemented to ensure secure access to user-specific data and functionalities.

4. **Frontend Implementation**:
    - HTML and CSS are used to design the user interface of the webpages, ensuring an intuitive and user-friendly experience.
    - JavaScript can be incorporated for client-side validation and dynamic interactions to enhance usability.

By integrating these components, the Pre-University Entrance Exam Seat Allotment System provides a comprehensive solution for managing user registration, login, student details, course information, and examination results, facilitating efficient communication and interaction between stakeholders involved in the pre-university education process.
