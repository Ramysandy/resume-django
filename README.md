# Resume Django Project

This project is a simple web application built with Django to display my resume online.

<img width="848" alt="Screenshot 2025-02-18 211350" src="https://github.com/user-attachments/assets/3965ee42-883e-425d-9f7d-0712b7ac0a31" />


## About

This project aims to create a clean and easily accessible version of my resume using the Django web framework. The resume is designed to be ATS-friendly (Applicant Tracking System) and presents my skills, experience, and projects in a clear and organized manner.

## Features

*   **Clean and Simple Design:** The resume is formatted with a focus on readability and ATS compatibility.
*   **Key Skills Highlighted:** Skills are categorized and prominently displayed.
*   **Experience and Projects Detailed:** Provides clear descriptions of my work experience and personal projects.
*   **Easy to Deploy:** The Django project is structured for easy deployment to various platforms.

## Technologies Used

*   **Django:** A high-level Python web framework for building web applications quickly and cleanly.
*   **HTML:** Used for structuring the resume content.
*   **CSS:** Used for styling the resume in a simple, formal black-and-white style.
*   **Git:** Used for version control.
*   **GitHub:** Used for hosting the project repository.

## How to Run Locally

1.  **Clone the repository:**

    ```
    git clone https://github.com/Ramysandy/resume-django.git
    cd resume-django
    ```

2.  **Create a virtual environment:**

    ```
    python -m venv venv
    ```

3.  **Activate the virtual environment:**

    *   On Windows:

        ```
        venv\Scripts\activate
        ```

    *   On macOS and Linux:

        ```
        source venv/bin/activate
        ```

4.  **Install dependencies:**

    ```
    pip install Django
    ```

5.  **Apply migrations:**

    ```
    python manage.py migrate
    ```

6.  **Run the development server:**

    ```
    python manage.py runserver
    ```

7.  **Open your browser and go to `http://127.0.0.1:8000/` to view the resume.**

## Creation Process

1.  **Project Setup:**
    *   Created a new Django project and app.
    *   Configured the project and app settings.
2.  **Resume Content:**
    *   Transferred the resume content from the `Shreeram_Sankar__resume.txt` file into the `resume.html` template.
    *   Formatted the content for readability and ATS compatibility.
3.  **URL Configuration:**
    *   Configured the `urls.py` files to map the root URL to the resume view.
4.  **Styling:**
    *   Created a `style.css` file for basic black-and-white styling.
5.  **Git Integration:**
    *   Initialized a Git repository.
    *   Created a `.gitignore` file.
    *   Committed the changes and pushed them to GitHub.


