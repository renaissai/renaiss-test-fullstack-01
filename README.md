# Renaiss Test Full-stack

![](res/banner.png)
# Description

The objective of the exercise is to evaluate the programming skills and the approach to solving the presented problem. For this, we propose creating a microservice usign FastAPI and a small frotend in React.

Good luck! 

<br>

# Exercise


## Poblem
---
A microservice is required to be created with login functionality and user registration, with access to a chat and a language model for chat history. 

The chat history must show the first message that the user sent to the chat and if he wants to access that history, show the rest of the messages.

The user can ask questions of a maximum of 2000 tokens and a maximum of 20 messages. The user must be informed as he progresses in his question the number of tokens left for that question and once the question is sent, he must inform how many questions he has left for that chat. Once the token limit is reached, it should not be allowed to continue writing and once the message limit has been reached, a new chat must be started.

You can use design references of Bing Chat or ChatGPT


The project must be developed using the following technologies:

- Frontend in Next.js with typescript.
- Frontend styles/components, but preferably using flowbite, styled components or tailwind. Design runs on your own, be creative.
- Backend in FastAPI
- Relational database (your choice)
- Queues (optional)
- Dockerized
- Authentication will be done through the use of JWT from the frontend. Chats will be saved in the style of chatgpt, allowing to start a chat from scratch.

## Evaluation
----
The evaluation process will focus on the following aspects:

- Application functionality
- Performance and optimization of multiple requests
- Frontend architecture. Preferably, you should use an architecture such as MVC to separate the logic from the component itself.
- Frontend protected routes.
- Frontend error boundary
- Frontend state managers
- Security of connections between frontend and backend
- Microservices architecture
- Code readability and project organization
- Logic and problem-solving
- The candidate's ability to create a scalable architecture, as well as their skill in optimizing application performance, will be valued. Their ability to organize code and effectively solve problems will also be taken into account.


...
