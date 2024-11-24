This Django-based web application allows managing multiple organizations, each with its own users and role-based access control. The system ables a Main Organization to see sub-organizations, while admins can manage users and assign roles within their respective organizations.

Key Features:
Organization Management:

The main organization can create and manage sub-organizations. Each sub-organization has its own users and roles.
Custom User Model:

The user model is extended to link each user to a specific organization.
Role Management:

Admins can assign roles like Admin, Editor, and Viewer to users, determining their access level within the organization.
User Management:

Admins can create, update, and delete users within their organization and assign them roles.
Access Control:

Only the main organization’s admin can manage sub-organizations. Similarly, only organization admins can manage users and assign roles.
Technology Stack:
Backend: Python, Django
Frontend: HTML, CSS, Bootstrap
Database: SQLite/MySQL
