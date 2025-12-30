# PPE-DETECTION
This project is a Personal Protective Equipment (PPE) Detection System built using the YOLOv11 deep learning model. It detects safety equipment such as helmets, masks, and safety vests from images or live video.

The system checks whether workers are following safety rules in real time. It is fast, accurate, and useful for construction sites, factories, and industrial areas. This project helps reduce accidents and improve workplace safety.

🚀 Features

Detects PPE items: Helmet, Mask, Safety Vest
Real-time object detection
High speed and accuracy
Works with images, videos, and live camera
Easy to deploy and extend

🛠️ Technologies Used

Python
YOLOv11
OpenCV
PyTorch
Computer Vision

📂 Dataset Details

The dataset contains images of people with and without PPE
Images are manually labeled with bounding boxes

Classes include:
Helmet
Mask
Safety Vest
No PPE

Dataset is split into:
Training set
Validation set
Test set

🧠 Model Architecture

YOLOv11 is a single-stage object detection model
It detects objects and classifies them in one pass
Uses convolutional neural networks (CNN)
Optimized for real-time performance
Produces bounding boxes with class labels and confidence scores

▶️ How It Works

Input image/video is given to the model
YOLOv11 processes each frame
PPE items are detected and labeled
Output is displayed with bounding boxes
Non-compliance can be identified easily

📈 Results

Accurate detection of PPE items
Works efficiently on CPU systems
Suitable for real-time monitoring
Reduces manual safety checks

🔮 Future Scope

Add sound or email alerts for no PPE
Integrate with CCTV cameras
Add face recognition for worker identity
Deploy as a web or mobile application
Improve accuracy with larger datasets

🏁 Conclusion

This project shows how deep learning and computer vision can be used to improve workplace safety. The PPE Detection System provides an automated and reliable solution for monitoring safety compliance in real time.
