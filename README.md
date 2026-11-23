# Self-Sorting Trash Can

**Academic engineering project | 2025–2026**

## Overview
A prototype that identifies waste from camera images and directs items into separate bins for paper, plastic, glass, and metal. The project combines image classification with microcontroller-controlled mechanical sorting.

## Technologies and components
ESP32-CAM · ATmega328P / Arduino Uno · Machine learning · Servo motors

## How it works
1. The ESP32-CAM captures an image of the item.
2. An image-classification model predicts its waste category.
3. The classification is passed to the ATmega328P-based controller.
4. Servo motors direct the item toward the corresponding bin.

## Implementation and results
- Built and tested a prototype using an ESP32-CAM, Arduino Uno, and servo motors.
- Tested classification across paper, plastic, glass, and metal categories.
- Observed occasional misclassifications; model training data and camera quality were identified as areas for improvement.

## Project media

<!-- Replace these placeholders after uploading your own materials. -->
- **Project report:** Add the PDF in a `report/` folder and link it here.
- **Hardware photographs:** Add selected photos in `images/` and link them here.
- **Circuit / simulation images:** Add schematics or screenshots in `images/`.
- **Demonstration video:** Add a link to your own video here (for example, an unlisted YouTube video).
- **Source code:** Add your own code in `src/` if available. Do not claim code is included until it is uploaded.

## Notes
This README summarizes the academic project. Add exact performance measurements only when supported by your original test records. Replace placeholder media links before sharing this repository with recruiters.
