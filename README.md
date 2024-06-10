# Sync-Chat

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a real-time chat application built using Go, Fiber, and HTMX. It allows users to join a single chat room and send messages in real-time. The backend is powered by Go and Fiber, a fast HTTP framework, while HTMX is used for dynamic, real-time interactions on the frontend without requiring a full page reload.

## Features

- Real-time messaging using WebSockets
- Single chat room
- User-friendly interface
- Lightweight and fast
- Easy to deploy

## Prerequisites

Before you begin, ensure you have the following installed:

- [Go](https://golang.org/dl/) (version 1.22 or later)
- [Fiber](https://gofiber.io/)
- [HTMX](https://htmx.org/)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/realtime-chat-app.git
    cd realtime-chat-app
    ```

2. **Install Go dependencies:**

    ```bash
    go mod download
    ```

## Configuration

Create a `.env` file in the root directory and add the following configuration variables:

```env
PORT=3000
 ```
You can modify the values according to your environment.

## Running the Application

1.Start the Go server:


    ```bash
    go run main.go
    
     ```
2.Open your browser and navigate to:

    ```bash
    http://localhost:3000
     ```
## Usage

- Open the app in your browser.
- Join the chat room.
- Start sending messages in real-time.

## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are reviewed on a regular basis.

1. Fork the repository
2. Create your feature branch 
3. Commit your changes 
4. Push to the branch 
5. Create a new Pull Request

## License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.

