# JU CampusCare: Smart Campus Complaint Management System

A browser-based prototype tailored for Jahangirnagar University (JU), Savar, Bangladesh.

## Features
- Student self-registration requires Full Name, Department/Institute, Batch, Hall Name, Email, and Password.
- Returning students sign in with their registered email and password.
- Private student dashboards: each student can view only complaints they submitted. Complaint details and ongoing cases are not shown on the public home page.
- Separate administrator sign-in to review complaints, set priority, and assign each complaint to Water, Electricity, Construction, Internet, Medical, or Others.
- Photo evidence, private status history, estimated resolution date, and CSV export.
- Department demo accounts and their credentials have been removed. Department assignment is managed through the administrator panel in this prototype.

## Run
Extract the ZIP and open `index.html` in a modern browser. No install is needed for this prototype.

## Demo account
- Admin: `admin@campuscare.edu` / `Admin@123`

Students should select **Create student account** on the student sign-in page and enter their own JU profile details. Existing students sign in with the email and password they registered.

## Prototype limitation
This is a frontend-only demonstration using browser `localStorage`. It is not production-secure and does not share data between different devices or browsers. A real deployment needs a Java Spring Boot backend, MySQL database, server-side authentication/authorization, and secure image storage. Never use the demo admin credentials in a live system.


Department staff login: use Department staff sign in on the login page. Water water@campuscare.edu / Water@123; Electricity electricity@campuscare.edu / Electric@123; Construction construction@campuscare.edu / Build@123; Internet internet@campuscare.edu / Internet@123; Medical medical@campuscare.edu / Medical@123; Others others@campuscare.edu / Others@123. Demo only, browser localStorage is not secure production authentication.
