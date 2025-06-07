# Chat Application

A real-time chat application built with Spring Boot, providing a modern and efficient way for users to communicate.

## Features

- Real-time messaging
- User authentication and authorization
- Modern and responsive UI
- Spring Boot backend
- WebSocket support for real-time communication

## Prerequisites

- Java 17 or higher
- Maven 3.6 or higher
- Your favorite IDE (IntelliJ IDEA, Eclipse, etc.)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/MahakAgrawal02/ChatApp
cd ChatApp
```

### Build the Project

```bash
mvn clean install
```

### Run the Application

```bash
mvn spring-boot:run
```

The application will start on `http://localhost:8081`

## API Endpoints

### WebSocket Endpoints

- WebSocket Connection: `ws://localhost:8081/chat`
- Message Broker Topics:
  - `/topic/messages` - Subscribe to receive chat messages
  - `/app/sendMessage` - Send a chat message

### REST Endpoints

- `GET /chat` - Returns the chat interface page

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── chat/
│   │           └── ChatAppApplication.java
│   └── resources/
│       └── application.properties
└── test/
    └── java/
```

## Technologies Used

- Spring Boot
- Spring WebSocket
- Spring Security
- Maven
- Java

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request