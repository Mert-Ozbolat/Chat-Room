<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chat Room App - README</title>
</head>
<body>
    <h1>🗨️ Chat Room App</h1>

    <h2>Preview:</h2>
    <img src="chat.gif"/>
    
    <p>
        A real-time chat application built using <strong>React</strong> for the frontend and <strong>Express</strong> for the backend. 
        This project leverages <strong>WebSocket</strong> technology to enable instant communication between users.
    </p>

    <h2>🚀 Features</h2>
    <ul>
        <li>Real-time messaging (powered by Socket.IO).</li>
        <li>Support for multiple chat rooms.</li>
        <li>Unique usernames for joining chat rooms.</li>
        <li>Message timestamps for clarity.</li>
    </ul>

    <h2>⚙️ Installation & Setup</h2>
    <ol>
        <li>Clone this repository:
            <pre><code>git clone https://github.com/your-username/chat-room-app.git
cd chat-room-app</code></pre>
        </li>
        <li>Install dependencies:
            <ul>
                <li>For the backend:
                    <pre><code>cd server
npm install</code></pre>
                </li>
                <li>For the frontend:
                    <pre><code>cd client
npm install</code></pre>
                </li>
            </ul>
        </li>
        <li>Start the application:
            <ul>
                <li>Start the backend server:
                    <pre><code>cd server
npm run start</code></pre>
                </li>
                <li>Start the frontend development server:
                    <pre><code>cd client
npm start</code></pre>
                </li>
            </ul>
        </li>
        <li>Open your browser and navigate to <code>http://localhost:3000</code> to use the chat room app.</li>
    </ol>

    <h2>📂 Project Structure</h2>
    <pre><code>chat/
├── client/       # React frontend
├── server/       # Express backend
├── README.md     # Project documentation</code></pre>

    <h2>📸 Screenshots</h2>
    <h3>Login Page</h3>
    <p>Users can join a chat room by entering their name and selecting a room.</p>

    <h3>Chat Room</h3>
    <p>Messages are updated in real time as they are sent and received.</p>
</body>
</html>
