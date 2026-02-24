REAL-TIME DOCUMENT EDITOR

COMPANY: CODTECH IT SOLUTIONS

NAME: SEJAL SANJAY UMBARKAR

INTERN ID: CTIS4947

DOMAIN: FULL STACK WEB DEVELOPMENT

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

TASK 2: REAL-TIME COLLABORATIVE DOCUMENT EDITOR
PROJECT TITLE: REAL-TIME DOCUMENT EDITOR USING YJS AND WEBSOCKETS
DESCRIPTION OF THE TASK

As part of my internship with CODTECH IT SOLUTIONS under the Full Stack Web Development domain, I successfully completed Task 2: Real-Time Document Editor, where I built a collaborative text editing web application.

The goal of this task was to develop a real-time collaborative editor that allows multiple users to edit the same document simultaneously and see changes instantly, just like Google Docs. The project uses Yjs (a CRDT-based synchronization library) and WebSockets for seamless communication between clients and the server.

This editor demonstrates the concept of real-time synchronization and peer collaboration using web technologies. When a user types in one browser window, the changes are instantly reflected on all other connected clients in the same room.

The server is built using Node.js, Express.js, and WebSocket (ws), which handles room-based communication between clients. On the client side, Yjs manages shared document states efficiently, ensuring conflict-free text editing.

The main purpose of this task was to understand bidirectional communication, implement real-time data synchronization, and gain practical experience with state management using CRDTs (Conflict-Free Replicated Data Types). This project enhanced my understanding of backend communication protocols, frontend collaboration logic, and synchronization consistency in multi-user environments.

OBJECTIVES

To understand and implement real-time collaboration using WebSockets.

To integrate Yjs for efficient CRDT-based document synchronization.

To design a minimal and responsive user interface for text editing.

To create a Node.js server that handles multiple client connections and synchronizes document data.

To ensure smooth, conflict-free collaboration between users editing the same document.

To add persistence for document storage and retrieval after server restarts.

TECHNOLOGIES USED

HTML5 – Structure of the web editor.

CSS3 – User interface styling and layout design.

JavaScript (ES6) – Frontend logic and DOM manipulation.

Node.js & Express.js – Backend server and REST handling.

WebSocket (ws) – Real-time, bidirectional communication between clients and server.

Yjs – Real-time CRDT synchronization library for collaborative editing.

WORKFLOW / IMPLEMENTATION

Project Setup:
The project includes two parts – the client (frontend editor) and the server (backend WebSocket handler). Both are initialized as separate Node.js applications.

Server Implementation:
The backend server is built with Express.js and WebSocket. It listens for connections, maintains room-based document states using Yjs, and broadcasts updates to all connected clients.

Client Implementation:
The client connects to the WebSocket server using Yjs. When a user edits the document, Yjs generates updates that are automatically synchronized with all connected clients in real-time.

Persistence Layer:
The editor saves and loads document data from the local file system (using Node.js fs module) so that text is preserved even after the server restarts.

Testing and Validation:
Multiple browser tabs are opened with the same room ID to verify simultaneous real-time updates and cross-tab synchronization.

RESULT / OUTCOME

The final Real-Time Document Editor successfully allows multiple users to edit and view live updates simultaneously. The synchronization is smooth, lag-free, and persistent. The project demonstrates my understanding of real-time web applications, WebSocket communication, and state synchronization with Yjs — key concepts in modern collaborative web development.
<img width="1919" height="1027" alt="Image" src="https://github.com/user-attachments/assets/3e40bbc2-4ca5-4c7f-a601-fc500006fe56" />
