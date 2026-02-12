# REAL-TIME-CHAT-APPLICATION

*COMPANY*:CODTECH IT SOLUTIONS

*NAME*:AbhinayaNagalla

*INTERN ID*:CTIS0222

*DOMAIN*:FRONTEND WEB DEVOLOPMENT

*DURATION*:8 WEEKS

*MENTOR*:NEELA SANTHOSH KUMAR

Task Description:

The task I performed was the design and implementation of a Real-Time Chat Application User Interface (UI) using HTML, CSS, and JavaScript, with Socket.IO for real-time communication. The goal of this project was to create a modern chat interface where users can send and receive messages instantly, simulating how real-world chat systems like WhatsApp, Messenger, or Slack work.

The chat application interface is structured into three main parts. At the top, a header section displays the title of the chat, ensuring users know they are in an active chat room. The central area is the chat box, which dynamically displays messages in order, with timestamps showing when each message was sent. At the bottom, an input area allows users to type messages and send them using a button. Messages are displayed instantly in the chat box and broadcast to all connected clients in real-time via the backend server.

During development, the HTML structure was used to define the core layout of the chat application. A main container wrapped the header, chat box, and input box. Within this container, semantic divisions (

) were created for each section, and elements like and were used to enable user interaction.
To make the chat UI user-friendly and visually appealing, CSS was applied. The container was styled with a soft whitesmoke background and rounded corners to create a modern card-like interface. The header was styled with a blue background and white text to stand out. The chat box had a scrollable area where all messages appeared neatly in bubbles. Each message included a timestamp in gray text for readability. The input field and button were styled with padding, borders, and hover effects, making the chat easy to use and visually engaging.

For interactivity and real-time functionality, JavaScript was used in combination with Socket.IO. The script established a WebSocket connection between the client (UI) and the backend server running on http://localhost:5000. When a user typed a message and clicked the Send button, the message was packaged with a timestamp and emitted to the server using the send_message event. The server then broadcasted the message to all connected clients, who listened for the receive_message event. The function addMessage() dynamically updated the chat window by appending new messages and auto-scrolling to the latest one. This allowed seamless two-way communication in real-time.

This task provided valuable experience in real-time web development, event-driven programming, and socket communication. It also reinforced concepts of DOM manipulation, dynamic updates without page reloads, and building interactive UIs that resemble real-world applications.

Tools Used:

HTML (HyperText Markup Language): Defined the structure of the chat interface, including header, chat box, input field, and buttons.

CSS (Cascading Style Sheets): Styled the UI for a modern and user-friendly look, with scrollable chat windows, styled message bubbles, and clear timestamp formatting.

JavaScript: Handled message sending, receiving, and updating the chat dynamically. Also implemented auto-scroll for smooth chat flow.

Socket.IO: Enabled real-time communication between client and server using WebSockets.

Git & GitHub (optional): For version control, collaboration, and hosting the chat application online.

Editor/Platform Used:

The project was developed using Visual Studio Code (VS Code). It provided syntax highlighting, integrated terminal support, and live server preview. The application was tested in Google Chrome to check message flow, timestamps, and UI responsiveness.

Applicability of the Task:

The Real-Time Chat Application has several real-world applications, including:

Messaging Systems: Building chat apps like WhatsApp, Messenger, or Slack.

Customer Support: Integrating live chat widgets into websites.

Collaboration Tools: Used in team communication apps for projects.

Gaming Platforms: Real-time player communication in multiplayer games.

E-learning Platforms: Providing direct student-teacher or peer chat features.

OUTPUT:
