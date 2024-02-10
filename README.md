# MusX Chat Web App

MusX Chat is a simple web chat application built using Flask and Socket.IO. Users can join existing chat rooms or create new ones to communicate with others in real-time.

## Features
- **Create or Join Rooms:** Users can either create a new chat room with a unique code or join an existing room using a provided code.
- **Real-time Communication:** The application uses Socket.IO to enable real-time messaging between users within the same chat room.
- **Responsive Design:** The web app is designed to be responsive, ensuring a seamless experience on both desktop and mobile devices.

## Prerequisites
Before running the application, make sure you have the following installed:
- Python 3
- Flask
- Flask-SocketIO

You can install Flask and Flask-SocketIO using the following commands:
```bash
pip install Flask
pip install flask-socketio
```

## Getting Started
1. **Clone the repository:**
    ```bash
    git clone https://github.com/musxeto/MusX-chat.git
    cd MusX-chat
    ```
2. **Run the application:**
    ```bash
    python app.py
    ```
3. Open your web browser and navigate to http://localhost:5000 to access the MusX Chat application.

## Usage
1. Enter your username and choose to either join an existing room by entering a code or create a new room.
2. Start chatting with other users in real-time.

## File Structure
- `app.py`: The main Flask application file containing the server-side logic.
- `templates/`: HTML templates for rendering the home and chat room pages.
- `static/`: Static assets such as CSS stylesheets and JavaScript files.

## Dependencies
- Flask
- Flask-SocketIO
- Bootstrap 5
- Socket.IO 4.0.1

## Customization
Feel free to customize the application by modifying the HTML templates or updating the CSS stylesheets according to your preferences.

## Contributing
If you'd like to contribute to the development of MusX Chat, please open an issue or submit a pull request. Your feedback and contributions are highly appreciated.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
