# AeroNova Drishti – Requirements Document

## 1. Problem Statement
During disasters like floods and earthquakes in India, real-time ground assessment becomes difficult due to communication failure and infrastructure damage. Rescue teams lack visibility on blocked roads, collapsed buildings, and stranded individuals.

## 2. Objective
To build an AI-powered disaster response system that analyzes aerial or satellite imagery in real-time and generates priority-based rescue insights.

## 3. Target Users
- National Disaster Response Force (NDRF)
- State Disaster Management Authorities
- Government Control Rooms
- Emergency Response Teams

## 4. Functional Requirements
- Real-time drone/satellite image ingestion
- AI-based object detection
- Detection of blocked roads, debris, collapsed buildings
- Identification of stranded individuals
- Live heatmap generation
- Rescue priority scoring
- Web dashboard for authorities

## 5. Non-Functional Requirements
- High detection accuracy
- Low latency processing
- Cloud scalability
- Secure data handling
- Reliable under high traffic conditions

## 6. Tech Stack
- YOLO / R-CNN for object detection
- AWS SageMaker for model hosting
- AWS Lambda for real-time processing
- AWS S3 for storage
- GIS-based heatmap dashboard

## 7. Assumptions
- Drone or satellite imagery is available
- Government agencies collaborate
- Cloud infrastructure is accessible

## 8. Constraints
- Internet disruption during disasters
- Limited drone availability in some regions
