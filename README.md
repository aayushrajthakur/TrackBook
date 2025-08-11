# TrackBook
An android application that record all the activity of phone including your location history, movement state, 3D parameters, etc


🧭 Roadmap: Activity Record App with Travel Visualization
📌 Phase 1: Planning & Requirements
✅ Goals
Track physical activity using accelerometer

Record location data and visualize travel paths

Store, analyze, and display activity metrics

Ensure data privacy and security

📋 Functional Requirements
Real-time sensor data capture

Activity classification (walk, run, sit, etc.)

GPS tracking and route mapping

Data storage (local/cloud)

UI for charts, maps, and summaries

Notifications and goal tracking

🔐 Non-Functional Requirements
Battery-efficient tracking

Secure data encryption

Scalable architecture

Offline support

🏗️ Phase 2: Architecture & Design
📦 Modules

<img width="928" height="555" alt="image" src="https://github.com/user-attachments/assets/6d1ba29c-85f3-4b60-9bd3-0b971fddc4b6" />



<img width="881" height="395" alt="image" src="https://github.com/user-attachments/assets/a6606853-1d0d-4744-a43d-bc7a296d81a5" />



🛠️ Phase 3: Development Milestones
🔹 Milestone 1: Sensor Integration
Access accelerometer and gyroscope

Log raw data with timestamps

🔹 Milestone 2: Activity Classification
Implement threshold-based logic

Optional: Train ML model for classification

🔹 Milestone 3: Location Tracking
Use GPS to log coordinates

Optimize sampling rate for battery

🔹 Milestone 4: Data Storage
Design schema for activity + location logs

Implement local DB and cloud sync

🔹 Milestone 5: Map Visualization
Plot daily/weekly routes on map

Add markers and overlays

🔹 Milestone 6: UI & Analytics
Build dashboard with charts

Show step count, distance, calories

🔹 Milestone 7: Security & Privacy
Encrypt logs using Hill cipher or AES

Manage permissions and user consent

🔹 Milestone 8: Testing & Optimization
Unit tests for modules

Profile battery and performance

Analyze cyclomatic complexity
