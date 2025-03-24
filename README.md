# Study Room Website (More features under development)

Welcome to the **Study Room Website**! This project allows users to manage their profile, create,update and delete their rooms. They can participate and visit other
users rooms, add comments and view content


---

## Features
- **Room Creation**: Users can create customizable study rooms for collaboration.
- **Real-Time Messaging**: Conversations within rooms to enhance interaction.
- **User Management**: Authentication for users to create and join rooms securely.
- **Responsive Design**: Built with HTML, CSS, and JavaScript for a seamless experience across devices.
- **Acitivity Feed** : This section updates recent activities across the websites in each users home page
- 
---

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default), easily configurable to other databases
- **Other Tools**:
  - minimalistic css
  - Django template system for dynamic content
---

## Getting Started

### Prerequisites
Make sure you have the following installed:
- **Python** (>= 3.6)
- **pip** (Python package manager)
- **Virtual Environment** (optional but recommended)
- **Django**
### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/study-room-website.git
    cd study-room-website
    ```
2. Set up a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run migrations:
    ```bash
    python manage.py migrate
    ```
5. Collect static files:
    ```bash
    python manage.py collectstatic
    ```
6. Start the development server:
    ```bash
    python manage.py runserver
    ```
7. Open the project in your browser:
    ```
    http://127.0.0.1:8000/
    ```
---

## Screenshots

```markdown
![Home Page](images/home-page.png)
![Room Creation](images/room-creation.png)
