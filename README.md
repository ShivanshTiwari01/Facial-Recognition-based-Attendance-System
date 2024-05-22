# Facial Recognition-Based Attendance System

This project is a facial recognition-based attendance system built using Flask, OpenCV, and machine learning. The system captures faces through a webcam, identifies them using a pre-trained model, and logs attendance data. 
The user interface is simple and built using HTML, CSS, and Bootstrap CSS.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Face Detection and Recognition**: Uses OpenCV to detect and recognize faces.
- **Attendance Logging**: Logs attendance with timestamp for recognized faces.
- **User Management**: Add and delete users with ease.
- **Model Training**: Trains a KNN model on captured faces.
- **Responsive UI**: Built with HTML, CSS, and Bootstrap for a clean and responsive interface.

## Installation

### Prerequisites
- Python 3.6+
- Virtual Environment (optional but recommended)

### Setup Instructions
1. **Clone the repository**
    ```bash
    git clone https://github.com/ShivanshTiwari01/facial-recognition-attendance-system.git
    cd facial-recognition-attendance-system
    ```

2. **Create a virtual environment** (optional but recommended)
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. **Install the dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Download the Haar Cascade file**
    - Download `haarcascade_frontalface_default.xml` from [OpenCV's GitHub repository](https://github.com/opencv/opencv/tree/master/data/haarcascades) and place it in the project root directory.

5. **Run the Flask application**
    ```bash
    python server.py
    ```

6. **Access the application**
    Open your web browser and go to `http://127.0.0.1:5000`.

## Usage

### Home Page
- Displays the current date and total registered users.
- Shows the list of attendees for the current day.

### Add User
- Navigate to the `Add User` page to register a new user.
- Enter the username and roll number, and capture face images using the webcam.

### List Users
- View all registered users with their details.

### Start Attendance
- Start the face recognition process by clicking on the "Take Attendance" button.
- The system will capture frames from the webcam, recognize faces, and log attendance.

### Delete User
- Navigate to the `List Users` page to delete a user.
- Select the user to be deleted, and their data will be removed from the system.


## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

