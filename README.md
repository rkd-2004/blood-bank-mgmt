# 💉 Blood Bank Management System

A simple **Blood Bank Management System** built using **Django** (Python), **HTML**, **CSS**, and **Bootstrap**.

## 📌 Features

- Register as a blood donor.
- Login system for users and admin.
- Admin can view, update, or delete donor details.
- Search blood donors by blood group and city.
- User-friendly interface.

## 🛠️ Technologies Used

- **Backend**: Python (Django)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default Django DB)

## 🚀 How to Run the Project

### 1. Clone the repository


git clone https://github.com/rkd-2004/blood-bank-mgmt
cd bloodbankmanagement


Create a virtual environment (optional but recommended)

python -m venv env
Activate the environment:

On Windows:


env\Scripts\activate
On Mac/Linux:


source env/bin/activate

3. Install dependencies

pip install -r requirements.txt

4. Run migrations

python manage.py makemigrations
python manage.py migrate

5. Create superuser (for admin access)

python manage.py createsuperuser
Follow the prompts to create the user.

6. Run the server

python manage.py runserver
Go to http://127.0.0.1:8000/ in your browser to view the app.
