Act as an expert full-stack web developer. Generate a complete, production-ready codebase and repository structure for a **Real-Time Multiplayer Live Quiz Web Application** (similar to Kahoot or Quizizz).

### 1. Technical Stack
- **Frontend**: Vanilla HTML5, CSS3 (with Tailwind CSS via CDN or modern CSS variables), and vanilla JavaScript (ES6+).
- **Backend**: Node.js with Express and **Socket.io** for real-time WebSocket communication.
- **Storage**: In-memory state management on the server (or simple JSON file storage for questions).

### 2. User Roles & Views
- **Host Dashboard (`host.html`)**: 
  - Create a new quiz room with a unique 4-digit PIN code.
  - View connected players in real-time.
  - Trigger questions, manage countdown timers, and display live scoreboards.
- **Participant View (`participant.html`)**:
  - Enter room PIN and nickname to join.
  - Receive synchronized questions and answer options on mobile or desktop.
  - View instant feedback (correct/incorrect) and current rank.

### 3. Key Features Required
- **Real-Time Sync**: Seamless synchronization of game states (lobby -> question -> countdown -> results -> leaderboard).
- **Scoring Algorithm**: Points awarded based on correct answers and response speed.
- **Responsive UI**: Mobile-first design with smooth CSS transitions, animations, and celebratory effects for winners.

### 4. Deliverables Needed
- Complete directory structure (`server.js`, `package.json`, and a `public/` folder containing the necessary HTML, CSS, and JS files).
- Step-by-step instructions in the `README.md` on how to install dependencies (`npm install`), start the server (`node server.js`), and test locally using multiple browser tabs.