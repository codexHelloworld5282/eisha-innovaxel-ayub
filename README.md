# eisha-innovaxel-ayub
# 🚀 URL Shortener – Flask App

A simple URL shortening service built with Python, Flask, and SQLite.

---

## ✏ **Features**
- Shorten any long URL into a unique shortcode.
- Auto-generate shortcode or use your own custom code.
- View and track click counts on original and short URLs.
- Update or delete existing short URLs.
- Simple web interface to manage URLs.

---

## ⚙ **Setup Instructions**
RUN in jupiter 

1. Clone the repository
git clone https://github.com/codexHelloworld5282/eisha-innovaxel-ayub.git
cd eisha-innovaxel-ayub

2. Switch to the dev branch
git checkout dev


3. Install dependencies
pip install flask

4. Run the app
 python ShortUrl.ipynb

How it works
Uses SQLite (urls.db) as local database.

generate_short_code() creates unique short codes.

Flask routes:

  1. / → Home page with list of all URLs

  2. /r/<shortCode> → Redirect to original URL

  3. /shorten → Create new short URL

  4. /update/<shortCode> → Update existing URL or code

  5. /delete/<shortCode> → Delete short URL


Tracks each click count (accessCount column).
