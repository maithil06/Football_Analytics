# Real-Time Object Detection and Tracking on Soccer Matches ⚽🎥

This repository contains a demonstration video (`annotated_output.mp4`) showcasing a computer vision model in action.  
The video features a soccer match with **real-time object detection, keypoint detection, and tracking** applied to identify players and the ball.

https://github.com/user-attachments/assets/30af69d5-14ba-4879-b65b-9bed1dd8a6f1

---

## 🚀 Key Features
- **Player Detection**: Identifies all players on the field.  
- **Team Classification**: Distinguishes between Manchester City and Chelsea players.  
- **Ball Detection**: Tracks the position of the soccer ball.  
- **Keypoint Detection**: Detects and tracks player body joints (e.g., arms, legs, torso).  
- **Confidence Scores**: Each detection is labeled with the model’s certainty level.  
- **Real-Time Tracking**: Bounding boxes, labels, and keypoints move smoothly as players navigate the field.  

---

## 🔎 How It Works
1. The model processes each frame of the input video.  
2. Objects (players, ball) are detected and annotated with:
   - Bounding box  
   - Keypoints (for player posture and movement)  
   - Label (team/player/ball)  
   - Confidence score  
3. Tracking algorithms ensure consistent IDs across frames.  

This approach is commonly used in **sports analytics, automated replays, coaching support, and live broadcasting**.

---

## 🛠️ Technical Details
- **Detection & Keypoints**: [YOLOv8](https://github.com/ultralytics/ultralytics)  
  - State-of-the-art for speed and accuracy  
  - Handles both bounding boxes and keypoint detection  
- **Tracking**:  
  - [ByteTrack](https://github.com/ifzhang/ByteTrack) or [DeepSORT](https://github.com/nwojke/deep_sort)  
  - Maintains unique IDs for each player and the ball  

---

## 📊 Potential Applications
- **Sports Analytics** 🏃‍♂️📈: Track player movement, formations, possession, and posture.  
- **Automated Replays** ⏪: Highlight goals, tackles, and key moments automatically.  
- **Coaching & Training** 🎯: Provide detailed visual feedback on player performance.  
- **Broadcasting** 📺: Enhance live matches with real-time overlays and stats.  

---

## 📂 Repository Contents
- `annotated_output.mp4` → Example demo video with full annotations.  
- *(Additional scripts/models can be added for replication and training.)*  

---

## 📌 Notes
This repository is intended as a **visual demonstration** for computer vision in sports.  
Feel free to use it for **educational purposes, research, or as a project showcase**.  

---
