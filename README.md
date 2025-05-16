# Ai-Chatbot
https://landbot.online/v3/H-2940045-C9V5MJLWN5LC9J2I/index.html
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f2f2f2;
}

/* Chat container style */
.chat-container {
    width: 350px;
    height: 500px;
    background-color: white;
    border-radius: 10px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    overflow: hidden;
}

/* Chatbox styles */
.chat-box {
    display: flex;
    flex-direction: column;
    height: 100%;
}

/* Messages container */
.messages {
    flex-grow: 1;
    padding: 10px;
    overflow-y: auto;
    border-bottom: 1px solid #ddd;
    background-color: #fafafa;
}

/* Individual message styling */
.message {
    margin: 10px 0;
    padding: 8px;
    border-radius: 15px;
    max-width: 70%;
}

.user-message {
    background-color: #4CAF50;
    color: white;
    align-self: flex-end;
}

.bot-message {
    background-color: #f1f1f1;
    color: black;
    align-self: flex-start;
}

/* Input and send button */
input[type="text"] {
    padding: 10px;
    border: none;
    border-top: 1px solid #ddd;
    flex: 1;
    font-size: 16px;
    border-radius: 0 0 0 10px;
}

button {
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 0 0 10px 0;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

button:active {
    background-color: #3e8e41;
}
