<img width="960" height="510" alt="image" src="https://github.com/user-attachments/assets/11eb70ab-da24-44a4-baeb-d1e653bc7af3" /># NoteTaker
NoteTaker is a web app built with Servlets, JSP, and Hibernate ORM. It allows users to create, update, and delete notes. Hibernate manages all database operations, ensuring smooth and efficient data persistence with MySQL.
## Features

- Create and save personal notes
- View all saved notes
- Edit or update existing notes
- Delete notes as needed
- Hibernate ORM for database interaction
- Clean and user-friendly interface using JSP

---

## Tech Stack

| Layer        | Technology            |
|--------------|------------------------|
| Frontend     | HTML, CSS, JSP         |
| Backend      | Java Servlets          |
| ORM          | Hibernate ORM          |
| Database     | MySQL                  |
| Server       | Apache Tomcat          |

---

## Folder Structure
NoteMaker/
├── src/
│ ├── com.notes.servlets/
│ ├── com.notes.entities/
│ ├── com.notes.helper/
├── WebContent/ or webapp/
│ ├── add_note.jsp
│ ├── edit_note.jsp
│ ├── all_notes.jsp
│ └── index.jsp
| |   add_notes.jsp
├── hibernate.cfg.xml
### Clone the Repository
bash
git clone https://github.com/username/NoteMaker.git

--Import Project into Eclipse
--Open Eclipse IDE
--File → Import → Existing Projects into Workspace
--Select the cloned project folder
--Set Up MySQL Database
--Create a MySQL database (e.g., notemaker)
--Update hibernate.cfg.xml with your DB credentials:
--Deploy on Tomcat Server
--Right-click project → Run As → Run on Server
--Make sure Apache Tomcat is configured
 ## Access the Application
 http://localhost:8080/NoteMaker/
 
 ## Learning Outcomes
Understanding MVC architecture with Servlets and JSP
Implementing Hibernate ORM for database operations
Working with dynamic web content and Java EE technologies

## Contact
Developer: Saumya Pandey
GitHub: @saumyapandey456
Email: saumya1617pandey@example.com

📄 License
This project is licensed under the MIT License — feel free to use it for learning and personal projects.
