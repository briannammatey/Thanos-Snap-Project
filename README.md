# Thanos-Snap-Project

Turn your snap into dust!  This was created in the Art and Computing Hackathon at Boston University 

This project uses **HTML, CSS, JavaScript, MediaPipe**, and **Matter.js** to detect your hand in real time and simulate it disintegrating into dust when you snap your fingers.

## ✨ Features

- **Real-time Hand Tracking** – Powered by [MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker) to detect your hand position and gestures.  
- **Snap Detection** – Recognizes the iconic “snap” gesture using hand landmark distances.  
- **Dust Physics Simulation** – Uses [Matter.js](https://brm.io/matter-js/) to create realistic particle scattering effects.  
- **Web-based** – Runs entirely in your browser with HTML, CSS, and JavaScript
## 📂 Project Structure
<img src="https://github.com/briannammatey/Thanos-Snap-Project/blob/main/thanos.png?raw=true" alt="Wordle Logo" width="300"/>


## ⚙️ How It Works

1. **Hand Tracking** – MediaPipe Hands detects 21 landmarks on your hand in real time.  
2. **Snap Detection** – The code measures the distance between your thumb and middle finger tips; a rapid close-and-open motion triggers the effect.  
3. **Dust Effect** – The detected hand area is converted into particles simulated by Matter.js.  
4. **Disintegration** – Particles scatter outward with random velocities and fade away, creating the “snap” effect.  

## 🛠️ Technologies Used

- **HTML / CSS / JavaScript** – Core web technologies  
- **[MediaPipe Hands](https://developers.google.com/mediapipe/solutions/vision/hand_landmarker)** – Real-time hand tracking  
- **[Matter.js](https://brm.io/matter-js/)** – Physics-based particle simulation  
- **Canvas API** – Rendering the dust effect  


## 🎯 Future Improvements

- Multi-hand detection and snapping  
- More cinematic particle rendering  
- Option to reverse the snap and reassemble the hand  
- Background music and visual effects toggle  
