# Multithreaded-WebServer
Skip to content
Navigation Menu
rohankharate750
Multithreaded-WebServer

Type / to search
Code
Issues
Pull requests
Actions
Projects
Security
Insights
Owner avatar
Multithreaded-WebServer
Public
rohankharate750/Multithreaded-WebServer
Go to file
t
Name		
rohankharate750
rohankharate750
Add files via upload
4075637
 · 
2 months ago
Multithreaded
Add files via upload
2 months ago
SingleThreaded
Add files via upload
2 months ago
ThreadPool
Add files via upload
2 months ago
README.md
Update README.md
2 months ago
Repository files navigation
README
Multithreaded-WebServer
A multi-threaded web server handles multiple client requests simultaneously by using separate threads for each connection, improving performance, scalability, and responsiveness. Multithreaded WebServer | Java Project This project is a Multithreaded WebServer built using Java that demonstrates the concepts of sockets, multithreading, and thread pooling to handle multiple client requests efficiently. The project includes a comparison between single-threaded and multi-threaded server performance.

📚 Project Overview The web server handles HTTP requests using TCP sockets and efficiently manages multiple client connections using multithreading. Key topics covered include:

Sockets and Client-Server Communication

TCP/HTTP Protocol Implementation

Multithreading, Context Switching, and Thread Blocking

Thread Pool and Event Loop Concepts

Single-Threaded vs Multi-Threaded Server Comparison

Thread Pool Implementation for Optimized Performance

📽️ Video Walkthrough The following is a timestamped breakdown of the project video:

⏰ Introduction to Sockets, Client-Server, and TCP/HTTP Communication

⏰ Understanding Multithreading, Thread Blocking, and Context Switching

⏰ ThreadPool and Event Loop Concepts

⏰ Coding a Single-Threaded WebServer

⏰ Coding a Multi-Threaded WebServer

⏰ Comparing Single-Threaded vs Multi-Threaded Server Performance

⏰ Implementing and Comparing Thread Pool Performance

⚙️ Features Single-Threaded Server: Handles one request at a time, making it inefficient under high load.

Multi-Threaded Server: Spawns a new thread for each client request, improving performance.

Thread Pool Implementation: Optimizes resource usage by managing a fixed number of threads.

🛠️ Technologies Used Java (JDK 11+)

TCP Sockets

Multithreading & ThreadPool

🚀 Getting Started

Clone the Repository bash Copy Edit git clone https://github.com/your-username/Multithreaded-WebServer.git cd Multithreaded-WebServer
Compile the Project bash Copy Edit javac MultiThreadedWebServer.java
Run the Server bash Copy Edit java MultiThreadedWebServer 📂 Project Structure bash Copy Edit /Multithreaded-WebServer ├── /src │ ├── SingleThreadedWebServer.java │ ├── MultiThreadedWebServer.java │ └── ThreadPoolWebServer.java └── /resources └── index.html 📝 Usage Instructions Run the server.
Open a web browser and navigate to http://localhost:8080.

The server will handle incoming requests and return the requested content.

📊 Performance Comparison Single-Threaded Server: Handles one request at a time, slower under high traffic.

Multi-Threaded Server: Creates a new thread per request, better for concurrent requests but may lead to high resource consumption.

Thread Pool Server: Manages a pool of threads, optimizes performance by limiting the number of threads created.

🤝 Contributing Contributions are welcome! Feel free to fork, submit issues, or make pull requests.

📄 License This project is licensed under the MIT License - see the LICENSE file for details.

About
A multi-threaded web server handles multiple client requests simultaneously by using separate threads for each connection, improving performance, scalability, and responsiveness.

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Java
100.0%
Footer
© 2025 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact
Manage cookies
Do not share my personal information
Editing Multithreaded-WebServer/README.md at main · rohankharate750/Multithreaded-WebServer
