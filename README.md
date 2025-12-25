Project Title: AI-Based Real-Time Students Tracking System Using CCTV

Project Status: 🚧 In Progress / Active Development
Current Phase: Prototype Testing & Feature Expansion
Institution: Vel Tech High Tech Dr. Rangarajan Dr. Sakunthala Engineering College 

Project Description

We are currently developing an automated campus management solution that transforms standard CCTV surveillance into an intelligent tracking system. This project aims to replace manual attendance methods with a touchless, AI-driven approach that handles student tracking, attendance marking, and safety monitoring in real-time.

Unlike static attendance apps, our system continuously analyzes video feeds to detect "bunking" (students present on campus but absent from class) and security threats.

Current Features (Implemented)


Multi-Camera Tracking: Capable of processing simultaneous video streams to track student movement across different campus zones.


Automated Attendance: Uses Face Recognition (MTCNN + dlib) to identify students and mark attendance automatically based on their class schedule.



Bunking Detection: Compares real-time location data against the timetable to flag students who are cutting classes.


Safety Alerts: A behavioral analysis module that detects unusual crowd formations or students entering restricted areas.


Dual Dashboard: A web-based interface built with Flask that provides separate views for Academic Faculty and Security Staff.

Development Roadmap (Future Work)

We are currently working on the following enhancements to improve system robustness:


Low-Light Optimization: Integrating infrared camera support and enhancing algorithms to improve detection accuracy in poor lighting conditions.


Crowd Density Adaptation: Refining the recognition algorithms to handle dense crowds and occlusion more effectively.


Mobile App Integration: Developing a companion mobile application for real-time alerts for faculty and parents.


Predictive Analytics: Implementing machine learning models to predict potential attendance issues based on historical behavioral patterns.


Edge Computing: Moving initial face detection to the edge (camera nodes) to reduce server load.

System Requirements

To run this project locally, the following hardware and software specifications are recommended:


Operating System: Ubuntu 20.04 LTS or Windows 10/11.


Python Version: Python 3.8+.


GPU: NVIDIA GPU (RTX 3060 or higher) with CUDA support is recommended for real-time deep learning inference.


Cameras: IP CCTV cameras with RTSP (Real Time Streaming Protocol) support.


RAM: Minimum 32GB recommended for handling multiple video streams.

Technology Stack


Core: Python, OpenCV, NumPy.


AI/ML: TensorFlow, Keras, dlib (Face Recognition), Scikit-learn.


Backend: Flask, Celery, Redis.


Database: PostgreSQL (optimized for JSONB embeddings).

Project Team

Dhanush D

Dhanush M

Donald Melvin A


Supervisor: Mr. G. Balaarunesh, Assistant Professor (AI&DS)
