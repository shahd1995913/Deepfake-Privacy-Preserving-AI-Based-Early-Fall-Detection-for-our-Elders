# Deepfake Privacy-Preserving AI-Based Early Fall Detection for Our Elders 
## Done by Shahed Al-khateeb 2025 AUGUST 

### Overview
This repository contains the implementation of an AI-based system designed to **preserve privacy** while performing **early fall detection** for elderly individuals.  
The system leverages **deepfake-based face replacement techniques** to anonymize personal identities in video feeds, ensuring that privacy is maintained during real-time monitoring and analysis.

The solution integrates:  

1. **Face Anonymization via Deepfake Technology** – Replacing the detected faces with synthetic, non-identifiable faces while preserving head pose and expressions.

| Target Image (Original) | Source Image (Features to Transfer) | Final Result (Face Swap) |
|-------------------------|------------------------------------|---------------------------|
| <img src="https://github.com/user-attachments/assets/1826e58d-702f-4a86-bf6e-e7aa090cfe01" width="300" height="300" /> | <img src="https://github.com/user-attachments/assets/b602d57f-10ce-41af-b961-1403a139e617" width="300" height="300" /> | <img src="https://github.com/user-attachments/assets/8318969a-9b8d-4046-ade2-948891eac566" width="300" height="300" /> |

<br>
<!-- https://huggingface.co/spaces/felixrosberg/face-swap
 -->
<!-- https://huggingface.co/spaces/felixrosberg/face-swap
--- -->


---
2.  **The face was recognized using MediaPipe, and the emotional state was identified using DeepFace** – Utilizing MediaPipe, such a perception pipeline can be built as a graph.  
<br>

| Result 1 | Result 2 |
|-------------------------|------------------------------------|
|  <img src="https://github.com/user-attachments/assets/9a01065f-ac87-4613-9963-30a7a8d6ab0b" width="300" height="300">|<img src="https://github.com/user-attachments/assets/f735f1ca-bf58-4cbb-83d9-a36a28716079" width="300" height="300"> |




---

3. **Mediapipe Pose (Pose Estimation)** – Utilizing deep learning techniques to detect the  state of the person standing, sleeping, or sitting

<img width="3840" height="2160" alt="image_4k (1)" src="https://github.com/user-attachments/assets/ce4375d0-1cc5-4e02-b3fb-8ec32848ecd0" />




---

4. **Early Fall Detection using AI Models** – Utilizing deep learning techniques to detect and predict potential falls before or as they occur, allowing timely assistance and intervention with Mediapipe Pose.
   
### Video used : [https://www.youtube.com/watch?v=D3gsPxbe9RA&t=203s ](https://www.youtube.com/watch?v=D3gsPxbe9RA&t=203s)


<img width="3840" height="2160" alt="image_4k (2)" src="https://github.com/user-attachments/assets/9d06e94e-15ad-4453-a777-884c6cffacd3" />

<img width="1010" height="393" alt="download (2)" src="https://github.com/user-attachments/assets/398925d9-041d-4fba-8dd6-c82b54f6b637" />

[![Video Demo](https://user-images.githubusercontent.com/xxxx/video_thumbnail.png)](https://github.com/shahd1995913/Deepfake-Privacy-Preserving-AI-Based-Early-Fall-Detection-for-our-Elders/blob/main/Early%20Fall%20Detection/annotated_output%20(1).mp4)



---

## How It Works
1. **Face Detection**: The system detects faces in the incoming video frames.  
2. **Face Replacement (Deepfake)**: Detected faces are replaced with synthetic faces generated to preserve expressions but anonymize identity.  
3. **Fall Prediction**: Motion features are extracted from the anonymized video and analyzed using the trained fall detection model.  
4. **Alert Mechanism**: When a fall is detected, the system can trigger alerts to caregivers or connected IoT devices.

---

## Applications
- **Elderly Care Homes**: Monitoring without compromising the dignity and privacy of residents.  

---

## Disclaimer
This project is intended for **research and educational purposes** only. 
