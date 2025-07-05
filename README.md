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

```

# Setup Instructions 🔧
1. Clone the Repository
git clone https://github.com/Vaishnavishatagopam77/Travel_Blog
cd sevenwonders

2. Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install Requirements
pip install django

4. Run the Development Server
python manage.py runserver
Open your browser and visit: http://127.0.0.1:8000/


# 📝 Features
🔗 Dynamic navigation with Home | About | Feedback links

📷 Fully templated wonder pages with unique backgrounds and content

📱 Mobile responsive layout

🧾 Feedback/contact form (Django Form or Google Forms optional)

# SCREENSHOTS
![Screenshot 2025-07-05 210257](https://github.com/user-attachments/assets/6f27f7f0-44a1-4334-b371-1325809d08bd)

![Screenshot 2025-07-05 210541](https://github.com/user-attachments/assets/588bfd15-117a-4b2a-992f-4be1ae78c3d4)

![Screenshot 2025-07-05 210629](https://github.com/user-attachments/assets/ab36fe43-f186-42b6-9153-4817fea025c2)

![Screenshot 2025-07-05 210629](https://github.com/user-attachments/assets/076583a4-4180-460a-95f9-d2f5569cde02)


# 🙌 Credits
Content and layout by Vaishnavi Shatagopam

Images sourced from Wikimedia Commons

Powered by Django 💡

# 📄 License
This project is licensed under the MIT License
