# ANPR-Garage-System
ANPR-based Garage System using Raspberry Pi

## Project Overview

This project aims to develop a Garage Management System leveraging Automatic License Plate Recognition (ANPR) technology using a Raspberry Pi. The system will collect and process vehicle data to manage parking efficiently, integrating sensors and actuators to simulate real-world scenarios.

## Objectives

- **Justification:** Analyze the current relevance of ANPR technology for managing parking lots.
- **Motivation:** Learn and apply machine learning models using single-board computers like Raspberry Pi, focusing on practical applications in IoT and automation.

## Methodology

1. **Data Collection:** Using a Raspberry Pi with a camera module to capture vehicle images at the garage entrance.
2. **Image Processing:** Employ a computer vision model(TBD), such as YoloV8 or Google AutoML, to recognize vehicle plates.
3. **Character Extraction:** Utilize OCR technologies(TBD) like Google Cloud Vision API or Tesseract OCR to extract text from the plates.
4. **Database Management:** Store extracted data (plate numbers, entry/exit times) in a database.
5. **Simulation:** Build a model garage using sensors and actuators to simulate parking lot operations, controlled by an ESP-32 microcontroller.

## Project Management

The project is managed using agile methodologies with four sprints planned:

1. **Sprint 1:** Component organization and technology familiarization.
2. **Sprint 2:** Initial setup of Raspberry Pi and peripherals, training the vision model.
3. **Sprint 3:** Cloud platform integration and text extraction technology setup.
4. **Sprint 4:** Final delivery, including a video and project presentation.

For more details, visit the [GitHub Project](https://github.com/users/filipinmello/projects/3).
