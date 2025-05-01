Django Social Media Website
A full-stack social media platform built with Django, allowing users to connect, share, and interact.

Features:

User Authentication: Sign up, log in, and log out functionalities.

Profile Management: Users can create and edit their profiles.

Post Creation: Users can create, edit, and delete posts.

Like and Comment: Interact with posts through likes and comments.

Follow System: Follow and unfollow other users to see their posts.

Responsive Design: Optimized for various devices using Bootstrap.

Installation:

Clone the repository:

git clone git@github.com:AdityaAgarwal1602/django-social-media-website.git
cd django-social-media-website

Create a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Apply migrations:

python manage.py makemigrations
python manage.py migrate

Run the development server:

python manage.py runserver\

Visit http://127.0.0.1:8000/ in your browser.


 Project Structure
├── core/
├── media/
├── social_book/
├── static/
├── templates/
├── db.sqlite3
├── manage.py
├── requirements.txt
└── README.md

Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

Contact
For any inquiries or feedback, please contact aditya.agr.2005@gmail.com.

