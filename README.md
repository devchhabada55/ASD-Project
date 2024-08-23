### Hi! Welcome to "Doc-AI : Enhanced Autism Spectrum Disorder Therapy Session Analysis with Computer Vision"

Title : Integrated IoT-based hardware-software codesign Approach/Mechanism for detecting Autism
spectrum disorder and interpretation.

Abstract : Autism Spectrum Disorder (ASD) is a developmental condition where patient faces challenges in
social interaction, communication and shows repetitive behavior. Symptoms and severity varies
in each individual. Traditional methods are often felt short for detecting an ASD as they were
time consuming and analyzed manually thus to overcome these issues this invention brings a
method to solve this problem. This patent showcases an advanced computer vision pipeline
designed to assess and evaluate therapist-child interactions during ASD therapy. By utilizing
complex models such as Detection Transformer (DETR),Face Emotion Detection (FER), Gaze
Transformer, and DeepFace, the system uses real-time object tracking, gaze pattern prediction
along with emotion detection, and extended video examination .Additionally we are using IOT
component such as EEG which generates the physiological data which gives insights regarding
the emotions and mental engagement levels By using the data which is gained by this complex
pipeline, this invention is able to generate comprehensive reports ,which are personalized for the
patient. This automation remarkably reduces the time and effort required for manual analysis,
thereby enhancing the overall assessment process and contributing to more efficient and tailored
therapy for children with ASD.

Whereas now just I have uploaded all files related to Software model.

Objectives : 
1. The objective of this project is to develop and build an advanced system which analyzes
therapist-child interactions during the therapy sessions.
2. The system integrates IoT devices such as EEG and a computer vision pipeline to
monitor real-time object interactions.
3. Recognizes emotions, predicts gaze patterns, and assesses the engagement levels of the
child.
4. By computerizing the assessment of the extended therapy session videos and
incorporating physiological data from EEG sensors, the project provides comprehensive,
precise insights.
5. Enhances therapeutic interventions and improves the accuracy and efficiency of ASD.


System Architecture for Integrated IoT-based hardware-software codesign :


![Object-Detection](https://github.com/user-attachments/assets/81ff487a-a98c-4157-bd0d-e0c85012f249)


Working Cycle for Software Model :
Video (input) -> Convert it into single frames -> extract frame -> first Process it with Object detection -> find physical engagement through movements -> find human-object interaction -> generate captions -> Annotate frames -> Generate video with annotations -> generate a detailed report

Computer vision models used :
1) Computer Vision Models:
2) Detection Transformer (DETR)
3) Face Emotion Detection (FER)
4) DeepFace
5) Gaze Transformer
