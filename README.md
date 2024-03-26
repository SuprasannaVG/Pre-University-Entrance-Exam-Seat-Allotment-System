# Pre-University-Entrance-Exam-Seat-Allotment-System
# Skills: SQL , Python, PHP, HTML-CSS
![Screenshot 2024-03-05 105436](https://github.com/SuprasannaVG/Pre-University-Entrance-Exam-Seat-Allotment-System/assets/125822020/7473edaf-3544-4e94-b15d-88759372e326)


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
       ![Screenshot 2024-03-27 000009](https://github.com/SuprasannaVG/Pre-University-Entrance-Exam-Seat-Allotment-System/assets/125822020/2417ba90-9c46-44b5-9aba-29ffb99c2a0e)

    - **Login Page**: This webpage enables registered users to log in by entering their credentials. Upon successful authentication, users are redirected to their respective dashboards.
      ![Screenshot 2024-03-26 235913](https://github.com/SuprasannaVG/Pre-University-Entrance-Exam-Seat-Allotment-System/assets/125822020/013a0a69-cbc8-4195-9b8b-54d788717134)
      
    - **Student Details Page**: This webpage displays and allows users to manage their personal information stored in the Student Details table. Users can update their details as necessary.
      ![Screenshot 2024-03-27 000258](https://github.com/SuprasannaVG/Pre-University-Entrance-Exam-Seat-Allotment-System/assets/125822020/60b3f117-30e9-417b-8a5c-f70c0bc99adf)
      ![Screenshot 2024-03-27 000331](https://github.com/SuprasannaVG/Pre-University-Entrance-Exam-Seat-Allotment-System/assets/125822020/631dc7a9-30ed-483a-ad3f-48b262ad2cb7)
      
    - **Course Details Page**: This webpage provides information about available courses, including descriptions, durations, and prerequisites, retrieved from the Course Details table.
      ![Screenshot 2024-03-05 103112](https://github.com/SuprasannaVG/Pre-University-Entrance-Exam-Seat-Allotment-System/assets/125822020/aa3f58f5-450c-4deb-a950-e3363d59dbf1)
      
      
    - **Result Page**: This webpage displays the results of the entrance exam or assessments stored in the Result table. Users can view their scores or ranks.
      
      ![Screenshot 2024-03-05 103212](https://github.com/SuprasannaVG/Pre-University-Entrance-Exam-Seat-Allotment-System/assets/125822020/623ec6d3-90e9-434d-95bf-b005e685fdfe)

      ![Screenshot 2024-03-19 131759](https://github.com/SuprasannaVG/Pre-University-Entrance-Exam-Seat-Allotment-System/assets/125822020/32ecdc45-9d8a-4223-928d-cfcfc2f29d57)
      
      ![Screenshot 2024-03-05 103247](https://github.com/SuprasannaVG/Pre-University-Entrance-Exam-Seat-Allotment-System/assets/125822020/add9aa5a-13fd-48a3-8f3e-06b05ed2185c)
     # Special Access to Admin
     
      ![Screenshot 2024-03-27 002316](https://github.com/SuprasannaVG/Pre-University-Entrance-Exam-Seat-Allotment-System/assets/125822020/c08a255d-7bb9-4a60-9b65-c81e67666888)

3. **Backend Implementation**:
    - The backend logic is implemented using Python and PHP for database interaction, user authentication, and data retrieval.
    - SQL queries are utilized to perform CRUD operations (Create, Read, Update, Delete) on the database tables.
    - Authentication mechanisms are implemented to ensure secure access to user-specific data and functionalities.

4. **Frontend Implementation**:
    - HTML and CSS are used to design the user interface of the webpages, ensuring an intuitive and user-friendly experience.
    - JavaScript can be incorporated for client-side validation and dynamic interactions to enhance usability.

By integrating these components, the Pre-University Entrance Exam Seat Allotment System provides a comprehensive solution for managing user registration, login, student details, course information, and examination results, facilitating efficient communication and interaction between stakeholders involved in the pre-university education process.


# Advantages:

1. **Efficient User Management**: The system facilitates efficient user management by allowing students to register and login securely, ensuring personalized access to their information and exam results.

2. **Streamlined Course Information**: By storing detailed course information in the database and providing a dedicated webpage, students can easily access and explore available courses, including descriptions, durations, and prerequisites, aiding them in making informed decisions about their academic paths.

3. **Centralized Student Details**: The system centralizes student details in a dedicated table, enabling easy management and updating of personal information. Students can conveniently access and modify their details through the user interface, ensuring data accuracy and completeness.

4. **Transparent Result Access**: Results of entrance exams or assessments are stored in the database and presented to students through a dedicated webpage. This transparency fosters trust and accountability in the evaluation process, empowering students to track their performance and plan accordingly for their academic pursuits.

5. **Enhanced Administrative Efficiency**: With organized user data and streamlined access to course details and exam results, administrators can efficiently manage student information, allocate resources, and make data-driven decisions to optimize the pre-university education system. This improves overall administrative efficiency and effectiveness.
