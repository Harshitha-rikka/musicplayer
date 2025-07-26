# musicplayer
# 🎵 Music Player with Playlist

A sleek and interactive web-based **music player** that lets users play, pause, and add songs to a **personalized playlist** using **HTML**, **JavaScript**, **PHP**, and **MySQL**.

---

## 📌 Key Features

- ✅ Play / Pause songs with real-time icon and label updates
- ✅ Add songs with title, artist, and cover image
- ✅ Store audio files in a dedicated folder (`/audio`)
- ✅ Maintain a custom playlist stored in MySQL
- ✅ View and play saved playlist in a separate page
- ✅ Clean and responsive UI with CSS styling

---

## 🛠️ Technologies Used

| Layer       | Tools/Technologies     |
|-------------|------------------------|
| Frontend    | HTML, CSS, JavaScript  |
| Backend     | PHP                    |
| Database    | MySQL (via XAMPP)      |
| Local Server| Apache (via XAMPP)     |

---

## 🗂️ Project Structure
musicplayer/
├── audio/ # Audio files (.mp3)
├── css/
│ └── style.css # Custom styles
├── js/
│ └── playjs.js # Audio playback logic
├── php/
│ ├── db_connect.php # Database connection
│ ├── mpfile.php # Add song to playlist
│ └── playopen.php # Display saved playlist
├── playlist.html # Main music player UI
├── index.html # Optional landing page
├── README.md # Project documentation
└── database.sql # SQL table structure
