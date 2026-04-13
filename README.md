# PolishPalette 💅✨

PolishPalette is an innovative, web-based nail salon booking platform that modernizes the appointment experience. By integrating a smart AI recommender, the system helps clients effortlessly discover and auto-build their perfect custom nail sets while providing artists with a seamless session management dashboard.

## Features

* **Clients:** Can use the Gemini AI Recommender to find custom nail designs based on text prompts, securely upload reference images, book appointments through a streamlined flow, and leave post-session ratings.
* **Artists:** Access a dedicated dashboard to view their visual work queue, approve or reject pending appointments, and manage active sessions using real-time start/finish timestamps.
* **Admins & Security:** Features robust security measures including Google OAuth integration, secure cloud image hosting, and comprehensive Admin Activity Logs to ensure non-repudiation and system auditing.

## Tech Stack

1. **Django** (Core Backend Framework)
2. **PostgreSQL** (Primary Relational Database)
3. **HTML5 / JavaScript** (Frontend Presentation)
4. **Bootstrap 5** (UI Styling & Responsive Layouts)
5. **Cloudinary** (Secure Reference Image Storage)
6. **Google Gemini AI API** (Smart Recommender Engine)

## Run Locally

1. Clone the project
```bash
git clone [https://github.com/your-username/polish-palette.git](https://github.com/your-username/polish-palette.git)
```

2. Go to the project directory
```bash
cd polish-palette
```

3. Create a virtual environment and activate it (Windows)
```bash
python -m venv env
env\Scripts\activate
```

4. Install dependencies
```bash
pip install -r requirements.txt
```

5. Set up Environment Variables
Create a `.env` file in the root directory and add your API keys:
```env
SECRET_KEY=your_django_secret_key
DEBUG=True
GEMINI_API_KEY=your_gemini_key
CLOUDINARY_URL=your_cloudinary_url
```

6. Run Database Migrations
```bash
python manage.py migrate
```

7. Start the Development Server
```bash
python manage.py runserver
```
```

***

### How to use this:
Just copy everything inside that black code block above, create a new file in your VS Code root directory called `README.md`, paste it in, and push it to GitHub. It will automatically format itself perfectly on the repository homepage.

Since the Admin Activity Logs are officially done, do you want to write the code for the **Artist Session Timestamps** next to completely finish out the backend logic?
