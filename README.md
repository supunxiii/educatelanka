![EducateLanka LMS Banner](https://github.com/supunxiii/supunxiii/blob/7653f59dcf38771e7791a1cc0795c9d6b4cdcd3c/user-interfaces/educatelanka/educatelanka-ui-1.png)

## Overview

EducateLanka is an online Learning Management System (LMS) developed for the COMP50022-K - Commercial Computing module. The platform supports the Sri Lankan school education system by improving access to learning resources, enabling structured feedback, and encouraging continuous student progress. It mitigates disruption during adverse weather and power cuts by providing reliable access to materials, and it helps reduce the digital divide across schools with a unified learning and communication hub. The assignment also demonstrates agile project management practices, including project initiation, planning, risk management, and closure activities with lessons learned.

![Django 4.2.3](https://img.shields.io/badge/Django-4.2.3-092E20?style=flat-square&logo=django&logoColor=white)
![Bootstrap 4.5.2](https://img.shields.io/badge/Bootstrap-4.5.2-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![SQLite 3.45.3](https://img.shields.io/badge/SQLite-3.45.3-003B57?style=flat-square&logo=sqlite&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-Markup-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Styles-1572B6?style=flat-square&logo=css3&logoColor=white)

## Features

EducateLanka provides the following features:

1. **Curriculum Structure**

   - Standards, subjects, and lessons organised with slugs and ordering
   - Subject-level listings with hierarchical navigation

2. **Lesson Content Management**

   - Lesson creation, updates, and deletion
   - File-based lesson resources (video, presentations, and notes)

3. **Interactive Learning**

   - Lesson comments and threaded replies
   - Timestamped discussion flow

4. **User Accounts and Profiles**

   - Registration and authentication
   - Profile metadata with user type (teacher, student, parent)

5. **Media Handling**

   - Profile images and subject imagery
   - Structured media storage per entity

6. **UI and Support**

   - Bootstrap-based responsive templates
   - Embedded Tawk.to live chat widget

## Technologies Used

- **Django 4.2.3**: Web framework (from `requirements.txt`)
- **asgiref 3.7.2**: ASGI utilities (from `requirements.txt`)
- **django-crispy-forms 2.0**: Form rendering utilities (from `requirements.txt`)
- **crispy-bootstrap4 2022.1**: Bootstrap 4 template pack (from `requirements.txt`)
- **Pillow 10.0.0**: Image processing (from `requirements.txt`)
- **sqlparse 0.4.4**: SQL parsing support (from `requirements.txt`)
- **tzdata 2023.3**: Time zone data (from `requirements.txt`)
- **SQLite 3.45.3**: Database engine (Python sqlite3 runtime)
- **Bootstrap 4.5.2**: UI framework (from template CDN)
- **HTML5**: Mark-up standard
- **CSS3**: Styling standard
- **Tawk.to API**: Embedded live chat widget
- **ClickUp**: Project management tool for agile workflow tracking

## Project Specifications

- **Course**: COMP50022-K - Commercial Computing
- **Domain**: LMS for Sri Lankan school education
- **Architecture**: Django MVT (Model-View-Template) with template-driven UI
- **Database**: SQLite3 (`db.sqlite3`)
- **Project Management**: Agile methods with initiation, planning, risk, time, cost, and procurement management

## User Interfaces

### UIs

![EducateLanka UI 2](https://github.com/supunxiii/supunxiii/blob/7653f59dcf38771e7791a1cc0795c9d6b4cdcd3c/user-interfaces/educatelanka/educatelanka-ui-2.png)

### UIs

![EducateLanka UI 3](https://github.com/supunxiii/supunxiii/blob/7653f59dcf38771e7791a1cc0795c9d6b4cdcd3c/user-interfaces/educatelanka/educatelanka-ui-3.png)

### UIs

![EducateLanka UI 4](https://github.com/supunxiii/supunxiii/blob/7653f59dcf38771e7791a1cc0795c9d6b4cdcd3c/user-interfaces/educatelanka/educatelanka-ui-4.png)

### UIs

![EducateLanka UI 5](https://github.com/supunxiii/supunxiii/blob/7653f59dcf38771e7791a1cc0795c9d6b4cdcd3c/user-interfaces/educatelanka/educatelanka-ui-5.png)

### UIs

![EducateLanka UI 6](https://github.com/supunxiii/supunxiii/blob/7653f59dcf38771e7791a1cc0795c9d6b4cdcd3c/user-interfaces/educatelanka/educatelanka-ui-6.png)

## Getting Started

To run EducateLanka locally, follow these steps:

1. Clone the repository:

   ```shell
   git clone https://github.com/supunxiii/educatelanka.git
   ```

2. Navigate to the project directory:

   ```shell
   cd educatelanka
   ```

3. Create and activate a virtual environment:

   ```shell
   python -m venv env
   source env/bin/activate
   ```

4. Install Python dependencies:

   ```shell
   pip install -r requirements.txt
   ```

5. Apply database migrations:

   ```shell
   python educatelanka/manage.py migrate
   ```

6. Start the development server:

   ```shell
   python educatelanka/manage.py runserver
   ```

7. Open the application in your browser:

   ```shell
   http://127.0.0.1:8000/
   ```

## Project Structure

```
educatelanka-main/
├── educatelanka/                      # Django project root
│   ├── app_users/                     # User profiles, registration, and login
│   ├── curriculum/                    # Standards, subjects, lessons, and comments
│   ├── educatelanka/                  # Project settings and URL configuration
│   ├── media/                         # Uploaded files
│   ├── static/                        # Static assets
│   ├── templates/                     # HTML templates
│   ├── db.sqlite3                     # SQLite database
│   └── manage.py                      # Django entry point
├── requirements.txt                   # Python dependencies
└── LICENSE                            # Project licence
```

## Contributors

This project was collaboratively developed by:

- **Supun Wijesooriya** - Lead Developer
- **Mandinee Hewage** - Developer
- **Ruchintha Thennakoon** - Developer

## Contributing

Contributions are welcome. If you would like to contribute:

1. Fork the repository.
2. Create a new branch:

   ```shell
   git checkout -b feature/your-feature-name
   ```

3. Commit your changes:

   ```shell
   git commit -m "Add your commit message"
   ```

4. Push your branch:

   ```shell
   git push origin feature/your-feature-name
   ```

5. Open a pull request with a clear description of your changes.

## License

This project is open-source and is licensed under the [MIT License](LICENSE).

## Contact

For any enquiries or feedback, please contact the developer:

- **Supun Wijesooriya**: [GitHub Profile](https://github.com/supunxiii)
- **Project Repository**: [educatelanka](https://github.com/supunxiii/educatelanka)

---

_Designed and developed in October 2023_

