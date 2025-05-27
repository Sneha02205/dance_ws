# Dance_ws  🎵💃

A Django-based web application to manage and showcase different dance styles, designed with modularity and scalability in mind.

## 🌟 Features

- Modular Django structure
- App for managing dance styles (`dance_styles`)
- Admin interface
- Well-organized settings and views
- Virtual environment configuration included

## 🏗️ Project Structure

DanceDjango/
├── dance_studio/ # Main Django settings and URL config
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── dance_styles/ # Custom Django app for dance content
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ └── apps.py
├── manage.py # Django management script
├── requirements.txt # Python dependencies
└── .venv/ # Python virtual environment (local)


## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- pip
- Virtualenv (optional but recommended)

### Installation

1. **Clone the repository**
   
   git clone https://github.com/Sneha02205/dance_ws.git
   cd DanceDjango

2. **Create a virtual environment**

python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

3. **Install dependencies**

pip install -r requirements.txt

4. **Run migrations**

python manage.py migrate

5. **Start the development server**

python manage.py runserver

###🧪 Testing

python manage.py test



