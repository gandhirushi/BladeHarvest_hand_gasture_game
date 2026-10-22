# ⚔️ Blade Harvest – Hand Gesture Game

**Blade Harvest** is a computer vision-based interactive game that allows players to control gameplay using real-time hand gestures instead of a traditional keyboard or mouse. The project uses a webcam to detect hand movements and translates them into in-game actions, creating an engaging touchless gaming experience.

## 🎮 Project Overview

The main objective of Blade Harvest is to interact with and slice objects on the screen by moving your hand in front of the webcam. The game combines computer vision, hand tracking, and game development to provide an intuitive and interactive experience.

## ✨ Features

- **Real-Time Hand Tracking:** Detects hand movements using a webcam.
- **Gesture-Based Controls:** Uses hand movements to interact with game objects.
- **Computer Vision:** Implements OpenCV for webcam and image processing.
- **Hand Landmark Detection:** Uses MediaPipe to track hand landmarks.
- **Interactive Gameplay:** Uses Pygame to manage game visuals and interactions.
- **Touchless Experience:** Allows gameplay without a physical controller.
- **Real-Time Interaction:** Converts detected hand movements into in-game actions.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| OpenCV | Webcam access and image processing |
| MediaPipe | Hand detection and landmark tracking |
| Pygame | Game development, rendering, and interaction |

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
```

Navigate to the project directory:

```bash
cd Blade-Harvest
```

> Replace `Blade-Harvest` with your actual project folder name if it is different.

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate the environment on Windows:

```bash
venv\Scripts\activate
```

On macOS or Linux:

```bash
source venv/bin/activate
```

### 3. Install Dependencies

Install the required Python libraries:

```bash
pip install opencv-python mediapipe pygame
```

If your project includes a `requirements.txt` file, you can install all listed dependencies using:

```bash
pip install -r requirements.txt
```

### 4. Run the Game

Run the main Python file:

```bash
python main.py
```

> If your main file has a different name, replace `main.py` with the correct filename.

## 🕹️ How to Play

1. Connect a webcam to your computer.
2. Start the game using the main Python file.
3. Allow the application to access your webcam.
4. Position your hand within the camera's view.
5. Move your hand to control the in-game slicing action.
6. Follow the game's on-screen instructions and try to achieve a high score.

*Note: The exact controls depend on the gestures and game mechanics implemented in the project.*

## 🧠 How It Works

The game follows a computer vision pipeline:

1. **Webcam Input:** OpenCV captures live video from the webcam.
2. **Hand Detection:** MediaPipe identifies the hand and detects its landmarks.
3. **Movement Tracking:** The application processes the detected hand position across video frames.
4. **Gesture Recognition:** Hand movement is interpreted as an input for the game.
5. **Game Interaction:** Pygame updates the game screen and processes the corresponding gameplay actions.

## 📂 Project Structure

An example project structure is shown below. Update the filenames to match your actual repository.

```text
Blade-Harvest/
│
├── main.py
├── requirements.txt
├── README.md
├── assets/
│   ├── images/
│   └── sounds/
└── venv/
```

## 💻 System Requirements

- Python 3.x
- A working webcam
- Windows, macOS, or Linux
- A computer capable of running real-time webcam processing
- Required Python libraries installed

## 🚀 Future Enhancements

- Add multiple difficulty levels.
- Improve gesture detection accuracy.
- Add sound effects and background music.
- Introduce a leaderboard and high-score tracking.
- Optimize performance for smoother gameplay.
- Add more interactive objects and gameplay modes.

## 🎯 Learning Outcomes

This project demonstrates practical implementation of:

- Computer vision and image processing.
- Real-time hand tracking using MediaPipe.
- Gesture-based human-computer interaction.
- Python game development using Pygame.
- Integration of multiple Python libraries into one application.

## 👨‍💻 Author

**Rushi Gandhi**

B.Tech – Artificial Intelligence and Data Science

## 📄 License

This project is intended for educational and learning purposes. Add a suitable open-source license if you plan to distribute the project publicly.
