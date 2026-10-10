# 🎵 RaagaWave – Music Playlist Sharing Platform

**RaagaWave** is a MERN-stack web application designed to make music discovery and playlist sharing simple and enjoyable. Users can explore songs, filter music by language or artist, save their favourite tracks, create playlists, and share playlists with others.

## 🚀 Project Overview

Music lovers often use different platforms to discover songs and manage their favourite music. RaagaWave aims to bring essential music discovery and playlist management features together in one user-friendly interface.

The application is built using the **MERN stack**: MongoDB, Express.js, React.js, and Node.js.

## ✨ Key Features

- 🔐 **User Authentication:** Sign-in and sign-up functionality.
- 🔍 **Song Search:** Search for songs using keywords.
- 🌐 **Language Filters:** Explore songs by language, such as Telugu, Hindi, Tamil, Kannada, and English, where metadata is available.
- 🎤 **Artist Search:** Discover songs by artist.
- ❤️ **Liked Songs:** Save favourite tracks for easy access.
- 🎶 **Playlist Management:** Create, view, update, and delete playlists.
- 🔗 **Playlist Sharing:** Share playlists with friends.
- ▶️ **Music Playback:** Integrate an authorised music provider where supported.
- 📱 **Responsive Design:** Provide a user-friendly experience across desktop and mobile screens.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| React.js | Frontend user interface |
| Node.js | Backend runtime |
| Express.js | REST API development |
| MongoDB | Database for users and playlists |
| JavaScript | Application logic |
| HTML5 & CSS3 | Structure and styling |
| Git & GitHub | Version control and collaboration |

## 🏗️ System Architecture

1. **Frontend:** React.js displays the interface and handles user interactions.
2. **Backend:** Node.js and Express.js process API requests.
3. **Database:** MongoDB stores user information, playlists, and related metadata.
4. **Music Provider:** An authorised external service can provide supported music catalogue and playback features.

## 📂 Project Structure

```text
RaagaWave/
├── client/              # React frontend
│   ├── public/
│   └── src/
├── server/              # Node.js and Express backend
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── server.js
├── README.md
├── .gitignore
└── package.json
```

*Note: Adjust this structure to match your actual repository.*

## ⚙️ Installation and Setup

### Prerequisites

- Node.js and npm
- MongoDB or a MongoDB Atlas connection
- Git
- Visual Studio Code or another code editor

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd RaagaWave
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your repository's actual URL.

### 2. Install dependencies

Install the frontend and backend dependencies according to your project structure.

```bash
cd client
npm install
```

If your backend has a separate `package.json`:

```bash
cd ../server
npm install
```

### 3. Configure environment variables

Create a `.env` file in the backend directory and configure the required values, for example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

Add authentication or music-provider credentials only if your implementation requires them. **Never upload passwords, API secrets, or private credentials to GitHub.**

### 4. Run the application

Start the backend using the script configured in its `package.json`, for example:

```bash
npm run dev
```

Start the React frontend in a separate terminal using the script configured in its `package.json`, for example:

```bash
npm run dev
```

The exact commands depend on your project configuration.

## 🧪 Testing

Test the following features during development:

- Song search and filters
- User sign-in and sign-up
- Playlist creation and editing
- Adding and removing liked songs
- Playlist sharing and access permissions
- Database persistence
- Music playback, if provider integration is configured

## 🔮 Future Enhancements

- Personalised music recommendations
- Public and private playlists
- Improved search and sorting
- Licensed lyrics integration
- More language and artist filters
- Progressive Web App support
- Automated testing and cloud deployment

## 🔒 Copyright and Music Access

RaagaWave is intended to use authorised music services or properly licensed content. Song availability, playback, and lyrics depend on the selected provider's API, permissions, and applicable terms.

## 👩‍💻 Project Information

- **Project Name:** RaagaWave – Music Playlist Sharing Platform
- **Project Type:** Web Application
- **Technology Stack:** MERN
- **Department:** Computer Science and Engineering

## 🤝 Contributing

Contributions and suggestions are welcome. You can fork the repository, create a feature branch, make your changes, and submit a pull request.

## 📄 License

Choose and add an appropriate open-source license before distributing the project. Music and other third-party content remain subject to their respective rights and licenses.

---

**RaagaWave – Discover music. Create playlists. Share your vibe. 🎧**
