# CHAT-APPLICATION-Full-Stack-web-

*COMPANY* : CODTECH IT SOLUTIONS

*NAME*: TEJAVATH AKSHARA

*INTERN ID*: CTSI0548

*DOMAIN*: FULL STACK WEB DEVELOPMENT

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOSH

##DESCRIPTION

*PROJECT REPORT: CHAT APPLICATION*

Building a real-time chat application for Task 2 of my CODTECH internship was a significant leap from the first assignment, moving from simple data fetching to the complex world of bi-directional, event-driven communication. In modern web development, users expect "live" experiences where information appears instantly without a page refresh. To meet the requirements of this task, I shifted my focus toward full-stack development, ensuring that both the frontend interface and the backend server logic worked in perfect harmony to facilitate instantaneous message exchange.​For the development environment, I continued to use Visual Studio Code (VS Code) as my primary editor. Its integrated terminal was essential for managing the Node.js environment and installing the necessary packages via NPM (Node Package Manager). To handle the real-time requirements, I utilized Socket.io, a powerful library built on top of the WebSocket protocol. While standard HTTP requests are "stateless" and close after one exchange, WebSockets keep a persistent tunnel open between the client and the server. This allows the server to "push" data to the client at any time, which is the foundational technology behind every modern chat and notification system we use today.​On the backend, I implemented a server using Node.js and the Express framework. The server's role in this architecture is to act as a central traffic controller. When a user types a message and hits send, the client "emits" an event to the server. The server then catches this event and immediately "broadcasts" it to every other connected user. I also integrated basic logging to track when users connect or disconnect from the socket, providing a glimpse into how session management works in a production environment. For the frontend, I used HTML5 and CSS3 to create a clean, "bubble-style" chat interface. I prioritized a mobile-first design approach, using Flexbox to ensure the message container and input field remain perfectly aligned and usable regardless of whether the user is on a desktop or a smartphone.​The logic within the browser was handled by Vanilla JavaScript. I wrote an event listener that intercepts the form submission, prevents the default page reload, and sends the message string through the socket. Simultaneously, the script listens for incoming message events from the server. When a new message arrives, the JavaScript dynamically creates a new list item and appends it to the chat window, auto-scrolling the view so the most recent conversation is always visible. This process perfectly illustrates the "Deliverable" required by the task: a live app with seamless frontend and backend integration.​The applications for this type of technology are incredibly diverse and go far beyond simple messaging apps. This "real-time" architecture is the backbone of Collaborative Tools like Google Docs, where multiple people edit a document simultaneously. It is used in Gaming for live multiplayer interactions and in Financial Services for stock tickers that update by the millisecond. It is also the standard for Live Support Portals used by major corporations to provide instant customer service. By completing this task, I have transitioned from building static pages to creating "living" applications that can handle active user sessions and high-frequency data updates. This project has solidified my understanding of server-side logic and the power of event-driven programming.

##OUTPUT

<img width="1148" height="1024" alt="Image" src="https://github.com/user-attachments/assets/ec7b91ab-7c70-47a2-bd94-ddc8a255c7e9" />
