# exam-protracting
Our project aims to develop a cheating detection model utilizing Convolutional Neural Networks (CNNs) to analyze head pose and pupil tracking data
Cheating detection is crucial for maintaining integrity and fairness. By leveraging advanced computer vision techniques, our model provides a non-intrusive and effective solution to identify suspicious behavior accurately.
Key Components:

Convolutional Neural Networks (CNNs): CNNs serve as the backbone of our cheating detection model. These deep learning architectures excel in extracting meaningful features from visual data, making them ideal for tasks like head pose estimation and pupil tracking.

Head Pose Estimation: Understanding the orientation of an individual's head is essential for detecting cheating behaviors such as looking away from the screen or towards unauthorized materials. By employing CNNs, we can accurately estimate head pose in real-time, enabling us to detect anomalous head movements indicative of cheating.

Pupil Tracking: Monitoring changes in pupil dilation or gaze direction can reveal valuable insights into an individual's focus and attention. Our model utilizes CNNs to track pupils robustly, allowing us to detect irregularities such as frequent shifts in gaze or prolonged periods of inattention.

Data Collection and Annotation: We collect a diverse dataset comprising samples of individuals engaging in various activities, including normal behavior and instances of cheating. Each sample is meticulously annotated with ground truth labels, facilitating supervised learning for our CNN-based model.

Training and Evaluation: We employ standard training procedures, including data augmentation and transfer learning, to train our CNN model on the annotated dataset. Subsequently, we rigorously evaluate its performance using metrics such as accuracy, precision, recall, and F1-score to ensure its efficacy in detecting cheating behavior accurately and reliably.
