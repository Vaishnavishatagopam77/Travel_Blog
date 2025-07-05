# Travel_Blog
The 7 Wonders Travel Blog – a digital journal dedicated to exploring the most breathtaking architectural and cultural marvels on Earth. Our goal is to take you on an adventure through history, geography, and global beauty — from the peaks of Machu Picchu to the mysteries of Petra.
# 🌍 7 Wonders Travel Blog (Django)

This is a Django-based web project that showcases the **Seven Wonders of the World** in the form of a clean, responsive travel blog.

Each wonder has its own dedicated page with history, itinerary suggestions, travel tips, and beautiful imagery — all served through a Django template engine.

---

## ⚙️ Tech Stack

- **Framework**: Django 4.x+
- **Frontend**: HTML5, CSS3, minimal JS
- **Template Engine**: Django Templates
- **Hosting Options**: GitHub Pages (static export), Render, Railway, or self-hosted


## 📁 Project Structure

```bash
sevenwonders/
├── manage.py
├── wonders/
│   ├── migrations/
│   ├── static/
│   │   └── wonders/
│   │       └── style.css
│   ├── templates/
│   │   └── wonders/
│   │       ├── index.html
│   │       ├── tajmahal.html
│   │       ├── petra.html
│   │       ├── greatwall.html
│   │       ├── colosseum.html
│   │       ├── chichenitza.html
│   │       ├── machu.html
│   │       └── christ.html
│   ├── urls.py
│   └── views.py
├── sevenwonders/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── README.md




## Setup Instructions 🔧
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/sevenwonders.git
cd sevenwonders
2. Create a Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Requirements
bash
Copy
Edit
pip install django
4. Run the Development Server
bash
Copy
Edit
python manage.py runserver
Open your browser and visit: http://127.0.0.1:8000/

🌐 Deployed Demo
Live site (if hosted): https://yourusername.github.io/sevenwonders

📝 Features
🔗 Dynamic navigation with Home | About | Feedback links

📷 Fully templated wonder pages with unique backgrounds and content

📱 Mobile responsive layout

🧾 Feedback/contact form (Django Form or Google Forms optional)

🙌 Credits
Content and layout by [Your Name]

Images sourced from Wikimedia Commons

Powered by Django 💡

📄 License
This project is licensed under the MIT License
