# Rocket Rust Chat App

A simple real-time chat application built with Rust using the Rocket framework and JavaScript for the frontend.

## Features
- Real-time messaging using Server-Sent Events (SSE)
- Multi-room chat functionality
- Simple and lightweight UI

## Technologies Used
- **Backend:** Rust, Rocket framework
- **Frontend:** JavaScript, HTML, CSS
- **Database:** None (messages are stored in memory)

## Installation & Running

### Prerequisites
- Rust (with Cargo)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/Abderahmantht/rocket-rust-chat-app.git
   cd rocket-rust-chat-app
   ```
2. Run the application:
   ```sh
   cargo run
   ```
3. Open your browser and go to:
   ```
   http://127.0.0.1:8000
   ```

## Usage
- Open multiple browser tabs to test real-time messaging.
- Type a username and message to send a message.
- Create and switch between chat rooms.

## File Structure
```
rocket-rust-chat-app/
├── src/
│   ├── main.rs        # Main Rocket server
│   ├── static/        # Frontend files (HTML, CSS, JS)
├── Cargo.toml         # Rust dependencies
├── README.md          # Project documentation
```

## License
MIT License

## Author
[Your Name]

