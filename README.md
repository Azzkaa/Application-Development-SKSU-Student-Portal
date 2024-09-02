
# Application-Development-SKSU-Student-Portal

The repository contains the source code for the SKSU Student portal project. Directory

SKSU Website ├── pycache ├── huza ├── uploaded_files ├── main.py (database connect, fastapi, all the APIs) ├── middleware.py (port configuration) ├── models.py (pydantic model) ├── frontend │ ├── package.json │ ├── postcss.config.js │ ├── public │ │ ├── assets │ │ │ └── images # All Project Images │ │ ├── favicon.ico │ │ ├── index.html │ │ ├── manifest.json │ │ └── robots.txt │ ├── README.md │ ├── src │ │ ├── App.jsx │ │ ├── assets │ │ │ └── fonts # Project fonts │ │ ├── components # UI and Detected Common Components │ │ ├── constants # Project constants, e.g., string consts │ │ ├── hooks # Helpful Hooks │ │ ├── index.jsx │ │ ├── pages # All route pages │ │ ├── Routes.jsx # Routing │ │ ├── styles │ │ │ ├── index.css # Other Global Styles │ │ │ └── tailwind.css # Default Tailwind modules │ │ └── util │ │ └── index.jsx # Helpful utils │ └── tailwind.config.js # Entire theme config, colors, fonts, etc. └── .gitignore # Gitignore file for the entire project

To start running the dev env for backend install the required dependencies for uvicorn and run this command: -uvicorn main:app --reload
To start running the dev env for frontend install the required dependencies for javascript react and tailwind, and run this command: -npm start


## Description: 

Application-Development-SKSU-Student-Portal is a comprehensive web-based platform designed to streamline the management of academic records, co-curricular activities, and administrative tasks within educational institutions. Developed using a Python-based backend with FastAPI and PostgreSQL, and a React.js frontend, the portal offers a user-friendly interface for students, parents, teachers, and administrators. It enables efficient data management, real-time tracking of co-curricular involvement, and easy access to academic records, enhancing the overall educational experience. The system is designed to cater to the diverse needs of educational stakeholders, providing a robust, scalable, and secure solution for modern education management.


## Students/Parents Web View 
![image](https://github.com/user-attachments/assets/c4bd61e3-6afc-4dce-93af-540c226c39a9)
![image](https://github.com/user-attachments/assets/e3ca2f41-a007-4d7f-ac6f-3bd148126ee7)
![image](https://github.com/user-attachments/assets/23ffd991-3908-484d-a20c-cdc8a1d8b13c)

## Teachers Web View 
![image](https://github.com/user-attachments/assets/c25c7a34-b07d-495d-aa4c-ed270e200664)
![image](https://github.com/user-attachments/assets/1df3e9bc-7faf-4c76-a0a5-f1fa244d7f01)
![image](https://github.com/user-attachments/assets/f31830e6-7dc0-43bc-b414-6f335337323e)
![image](https://github.com/user-attachments/assets/fa8d12a8-3e7d-4675-b335-c471534eecca)
![image](https://github.com/user-attachments/assets/d20a2143-0aa4-4a98-bcbb-7f851fbb74c2)
![image](https://github.com/user-attachments/assets/1430ecef-9fb8-49a3-a033-1c21f18d7624)

## Administrator View 
![image](https://github.com/user-attachments/assets/c00a6123-dd82-4f92-a97b-48d82451815e)
