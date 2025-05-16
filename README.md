# Smart India Hackathon Workshop
## Date: 15.05.2025

## Register Number: 212222230152

## Name:Suji

## Problem Title:
AI-Based Smart Surveillance and Women Safety System in Public Transport

## Problem Description:
Background:
Incidents of harassment and crime against women in public transport systems (buses, trains, metro) remain a significant concern. Traditional CCTV surveillance is reactive, requiring manual monitoring. There’s a need for an AI-driven, real-time alerting system that enhances safety, enables instant response, and promotes confidence among women passengers.

## Expected Solution:
A real-time video surveillance system integrated with AI that can detect abnormal or threatening behavior inside public transport vehicles and instantly alert the authorities. The system should be scalable, privacy-compliant, and capable of running on edge devices or with cloud support.

## Idea
SafeCommuteAI – A smart safety platform with onboard cameras powered by AI to detect:

Aggressive gestures

Unusual crowd patterns

Unattended objects (for security)

Panic/emergency signals from passengers

## Includes:

Passenger-triggered safety alert buttons

Real-time alerts to control rooms

Live tracking and video stream during alerts

Women-only safety feature activation (voice-commanded SOS)

## Proposed Solution / Architecture Diagram
### Solution Features:
AI-powered cameras in public transport.

Real-time threat detection and behavior analysis.

In-vehicle panic button & mobile app emergency trigger.

Control room alert system with live stream.

Integration with city surveillance systems and police networks.

Privacy-first architecture (faceless detection, only behavioral metrics).

## Architecture Diagram (Text-Based)
![image](https://github.com/user-attachments/assets/a458d154-6993-4db3-aef8-27849979cada)

## Use Cases
In-Transport Alert: AI detects aggressive behavior → alerts central team + shows live feed.

SOS Trigger: A woman presses panic button or gives a voice command → alert sent + bus stops at safe zone.

Suspicious Object Detection: Identifies abandoned bags for bomb threat prevention.

Night Mode: Increases AI alert sensitivity during low-passenger night routes.

Integration with Police Station: Instant redirection of feed and alert to nearest police station.

## Technology Stack
Edge Devices: NVIDIA Jetson Nano / Raspberry Pi with camera

AI Models: OpenCV + YOLOv8 (for gesture recognition, object detection)

Backend: Node.js / FastAPI

Dashboard: React.js + Mapbox

Notifications: Firebase Cloud Messaging, Twilio SMS

Mobile App (Optional): Flutter

## Dependencies
Pre-trained behavior detection models (OpenPose, ActionNet)

Public transport integration support (hardware, access to routes)

Edge computing devices

Police/transport department API access for emergency routing

High-speed mobile internet / 5G module for live feed


