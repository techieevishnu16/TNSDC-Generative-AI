# TNSDC-Generative-AI
# Emotion-Based playlist Recommendation

This project analyzes emotions in images and recommends music based on the detected emotion.

## Overview

The project utilizes the DeepFace library to analyze emotions in images. It extracts the dominant emotion from the image and recommends songs corresponding to that emotion. The recommendation is based on a pre-defined dataset of songs tagged with various moods/emotions.

## Installation

To use this project, you'll need Python installed on your system or use Google colab. Additionally, you need to install the required libraries. You can install them using pip.

## Usage
1.Ensure you have your images ready for emotion analysis.
2.Replace the image_location variable in the provided code with the path to your image.
3.Run the provided code.
4.The detected emotion and recommended songs will be displayed.

## Example usage
image_location = '/path/to/your/image.jpg'
detected_emotion = analyze_emotion_in_image(image_location)
print("Detected Emotion:", detected_emotion)
get_songs_by_emotion(detected_emotion)

## Dataset
The music dataset (data_moods.csv) contains information about songs categorized by mood/emotion. This dataset is used to recommend songs based on detected emotions.

## Credits
*DeepFace: Library for face recognition and facial attribute analysis.
*Pandas: Library for data manipulation and analysis.
*OpenCV: Library for computer vision tasks.

