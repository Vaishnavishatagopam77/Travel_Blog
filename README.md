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


---

# Setup Instructions 🔧
1. Clone the Repository
git clone https://github.com/yourusername/sevenwonders.git
cd sevenwonders

2. Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install Requirements
pip install django

4. Run the Development Server
python manage.py runserver
Open your browser and visit: http://127.0.0.1:8000/

##🌐 Deployed Demo

#📝 Features
🔗 Dynamic navigation with Home | About | Feedback links

📷 Fully templated wonder pages with unique backgrounds and content

📱 Mobile responsive layout

🧾 Feedback/contact form (Django Form or Google Forms optional)

# SCREENSHOTS
(https://github.com/user-attachments/assets/5da189f4-4383-4be7-8165-e05fe19091af)
(https://github.com/user-attachments/assets/780ef39c-c79e-424e-a4d3-b415c5f12ac2)
(https://github.com/user-attachments/assets/3c6978e7-ad14-47d8-9fc2-f6edc458352c)
(https://github.com/user-attachments/assets/82f03b32-4d95-44f2-b47a-5b4fb666dc67)


# 🙌 Credits
Content and layout by Vaishnavi Shatagopam

Images sourced from Wikimedia Commons

Powered by Django 💡

# 📄 License
This project is licensed under the MIT License
