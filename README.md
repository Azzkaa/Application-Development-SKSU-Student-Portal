
# Application-Development-SKSU-Student-Portal

The repository contains the source code for the SKSU Student portal project. Directory

SKSU Website ├── pycache ├── huza ├── uploaded_files ├── main.py (database connect, fastapi, all the APIs) ├── middleware.py (port configuration) ├── models.py (pydantic model) ├── frontend │ ├── package.json │ ├── postcss.config.js │ ├── public │ │ ├── assets │ │ │ └── images # All Project Images │ │ ├── favicon.ico │ │ ├── index.html │ │ ├── manifest.json │ │ └── robots.txt │ ├── README.md │ ├── src │ │ ├── App.jsx │ │ ├── assets │ │ │ └── fonts # Project fonts │ │ ├── components # UI and Detected Common Components │ │ ├── constants # Project constants, e.g., string consts │ │ ├── hooks # Helpful Hooks │ │ ├── index.jsx │ │ ├── pages # All route pages │ │ ├── Routes.jsx # Routing │ │ ├── styles │ │ │ ├── index.css # Other Global Styles │ │ │ └── tailwind.css # Default Tailwind modules │ │ └── util │ │ └── index.jsx # Helpful utils │ └── tailwind.config.js # Entire theme config, colors, fonts, etc. └── .gitignore # Gitignore file for the entire project

To start running the dev env for backend install the required dependencies for uvicorn and run this command: -uvicorn main:app --reload
To start running the dev env for frontend install the required dependencies for javascript react and tailwind, and run this command: -npm start



## Description: 

Application-Development-SKSU-Student-Portal is a comprehensive web-based platform designed to streamline the management of academic records, co-curricular activities, and administrative tasks within educational institutions. Developed using a Python-based backend with FastAPI and PostgreSQL, and a React.js frontend, the portal offers a user-friendly interface for students, parents, teachers, and administrators. It enables efficient data management, real-time tracking of co-curricular involvement, and easy access to academic records, enhancing the overall educational experience. The system is designed to cater to the diverse needs of educational stakeholders, providing a robust, scalable, and secure solution for modern education management.
## Students/Parents Web View 


## Teachers Web View 
## Administrator View 