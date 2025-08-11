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
Module	Description
Sensor Manager	Captures accelerometer and gyroscope data
Activity Classifier	Detects user activity using thresholds or ML
Location Tracker	Collects GPS coordinates
Map Renderer	Displays travel path on map
Data Logger	Stores activity and location data
UI Dashboard	Visualizes metrics, charts, and maps
Notification Engine	Sends alerts and reminders
Security Layer	Encrypts sensitive data
🧱 Suggested Tech Stack
Layer	Technology
Frontend	Android (Java/Kotlin), iOS (Swift)
Backend	Firebase / SQLite / Room
Maps	Google Maps SDK / Mapbox
ML (optional)	TensorFlow Lite / Core ML
Encryption	Custom Hill cipher / AES
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
