# Dr. Varinder Arora Clinic Website

## 🗂️ Project Structure

```
dr-varinder-arora-clinic/
│── index.html          ← Homepage (main file)
│── about.html          ← About Doctor page
│── contact.html        ← Contact / Query page
│── package.json
│── css/
│   └── styles.css
│── js/
│   └── script.js
│── server/
│   └── server.js       ← Node.js backend
│── data/
│   ├── appointments.json
│   └── queries.json
│── images/             ← PUT YOUR IMAGES HERE
│   ├── hero-bg.jpg     ← Homepage hero background
│   └── doctor.jpg      ← Doctor photo (About page)
```

---

## 🖼️ IMAGE GUIDE

You need **2 images** total. Place them inside the `/images/` folder.

| File Name     | Where Used       | Recommended Size  | What to Use                              |
|---------------|------------------|-------------------|------------------------------------------|
| `hero-bg.jpg` | Homepage hero    | 1920×1080 px      | Clinic reception, hospital corridor, or any professional medical background |
| `doctor.jpg`  | About page       | 400×500 px (portrait) | Doctor's professional photo (standing or sitting in clinic) |

### How to rename your photos:
1. Take any clinic/hospital background photo → rename it exactly to `hero-bg.jpg`
2. Take Dr. Varinder Arora's photo → rename it exactly to `doctor.jpg`
3. Put both inside the `images/` folder

> **Note:** If images are missing, the site still works — it shows a gradient/placeholder instead.

---

## ▶️ HOW TO RUN

### Step 1: Install Node.js
Download from: https://nodejs.org (v18 or newer)

### Step 2: Open Terminal / Command Prompt
Navigate to the project folder:
```
cd dr-varinder-arora-clinic
```

### Step 3: Install dependencies
```
npm install
```

### Step 4: Start the backend server
```
npm start
```

You'll see:
```
  ╔═══════════════════════════════════════╗
  ║  Dr. Varinder Arora Clinic — Server   ║
  ║  Running at http://localhost:3000      ║
  ║  Admin:   http://localhost:3000/admin  ║
  ╚═══════════════════════════════════════╝
```

### Step 5: Open the website
Open your browser and go to:
```
http://localhost:3000
```

---

## 🔗 Pages

| URL                              | Page               |
|----------------------------------|--------------------|
| http://localhost:3000            | Home               |
| http://localhost:3000/about.html | About Doctor       |
| http://localhost:3000/contact.html | Contact / Query  |
| http://localhost:3000/admin      | Admin Dashboard    |

---

## 📋 Features

- ✅ Appointment booking with modal popup
- ✅ Dark / Light mode toggle
- ✅ Parallax hero effect
- ✅ Scroll animations
- ✅ Stats counter
- ✅ Testimonial slider
- ✅ Contact/query form
- ✅ Admin dashboard at /admin
- ✅ Responsive (mobile + tablet + desktop)
- ✅ Scroll progress bar
- ✅ Loading animation

---

## ⚙️ Without Backend (frontend only)
Open `index.html` directly in a browser. Forms will still work — data is saved to browser localStorage instead of the server. No Node.js needed for just viewing the site.
