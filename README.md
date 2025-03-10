# Hand Gesture Security System

## Overview

The **Hand Gesture Security System** is an AI-powered security solution that utilizes computer vision and machine learning to recognize specific hand gestures, detect potential threats, and notify authorities. Built with OpenCV and MediaPipe, this system enables users to define custom gestures for security alerts and integrates with a dashboard for real-time monitoring.

## Features

- **Real-time Hand Gesture Recognition**: Uses OpenCV and MediaPipe to detect hand gestures.
- **Customizable Gestures**: Users can define gestures to trigger alerts.
- **Threat Detection**: Recognizes predefined gestures indicating a security threat.
- **Automated Image Capture**: Captures and uploads images of the detected threat.
- **Dashboard Integration**: Sends alerts and images to an authority’s dashboard for monitoring.

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- OpenCV
- MediaPipe
- NumPy
- Flask (for the dashboard, if used)

### Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/hand-gesture-security.git
   cd hand-gesture-security
   pip install -r requirements.txt
   python main.py


