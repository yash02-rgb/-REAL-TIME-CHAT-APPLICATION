# -REAL-TIME-CHAT-APPLICATION
*COMPANY*: CODETECH IT SOLUTION
*NAME*: YASH DAGAR
*INTERN ID*: CT04DG1684
*DOMAIN*: FRONTEND WEBDEVELOPMENT
*MENTOR*: NEELA SANTOSH KUMAR

# DESCRIPTION:📄 Real-Time Chat Application 
This project is a real-time chat application built using React.js on the frontend and WebSockets for communication. The main goal was to create a responsive interface where two users (or a user and a server) could exchange messages instantly — mimicking the behavior of popular chat apps like WhatsApp or Messenger but on a basic level.

🧩 What I Tried to Build
The idea was to develop a working chat window that sends and receives messages in real time. I used a public echo WebSocket service for this, which basically bounces back any message you send — helping to simulate a real conversation without needing a backend server setup.

Messages appear in a scrollable chat window, with different background colors depending on who sent the message — you (the user) or the server (simulated reply). It looks like a basic chat room, and everything updates instantly as messages are sent.

🛠️ Technologies Used
React.js for building the UI and handling state.

WebSocket API to handle real-time communication.

Plain CSS for styling — no frameworks like Bootstrap or Tailwind were used.

JavaScript Hooks like useState, useEffect, and useRef for handling logic and side effects in React.

📱 Features I Included
A simple input field where users can type messages.

A submit button and also the ability to hit Enter to send.

Live message updates — you send a message and see a response instantly.

Full chat history displayed on the screen.

Basic styling with message bubbles aligned differently for sent and received messages.

Responsive design — works on both desktop and mobile.

🧠 What I Learned
Working on this helped me understand how real-time apps work under the hood. I got a better grasp of how WebSocket connections are opened, how messages are sent and received, and how to manage message state inside a React component. It was also a good exercise in managing clean UI updates and keeping the WebSocket connection stable across renders.

One tricky part was making sure the chat didn’t refresh or lose messages, so I had to make sure state updates were handled properly using React’s hooks. Another challenge was making the design mobile-friendly without relying on any heavy frameworks.
