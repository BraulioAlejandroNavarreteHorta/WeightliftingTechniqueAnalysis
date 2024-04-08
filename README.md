# Weightlifting Technique Analysis

This project utilizes computer vision, artificial intelligence, and machine learning with MediaPipe to conduct an exhaustive analysis of weightlifting techniques. The goal is to detect correct and incorrect techniques during weightlifting exercises to help athletes avoid injuries by optimizing their form.

## Project Overview

The repository contains Python scripts and Jupyter Notebooks that process video data of weightlifting exercises. It applies MediaPipe models to analyze the posture and movements of athletes, identifying proper and faulty techniques in exercises like squats and bench presses.

## Contents

- Python Scripts:
  - `calculate_angle.py`: Utility script for angle calculations.
  - `mp_pose_envivo.py`, `mp_pose_envivoPress.py`, `mp_pose_envivoSentadilla.py`: Real-time pose estimation scripts for various exercises.
  - `mp_pose_image.py`: Image analysis for pose estimation.
  - `mp_pose_video.py`: Pose estimation in pre-recorded videos.
  - `press_de_banca_buena_tecnica.py`, `press_de_banca_mala_tecnica.py`, `sentadilla_buena_tecnica_beto.py`, `sentadilla_buena_tecnica_dono.py`, `sentadilla_mala_tecnica_beto.py`, `sentadilla_mala_tecnica_dono.py`: Analysis scripts for specific exercises and techniques.
- Jupyter Notebooks:
  - `Pruebas.ipynb`: Testing and experimentation notebook.
  - `SegmentacionVideos.ipynb`: Notebook for video segmentation and processing.
- Videos:
  - Sample exercise videos and their analyzed results demonstrating both good and bad techniques.

## Installation and Usage

Ensure you have the following prerequisites installed:
- Python 3
- MediaPipe
- OpenCV
- Other dependencies that can be installed via `pip`.

## Acknowledgements

- A special thanks to the athletes who participated in the video recordings.
- The developers and researchers who contributed to the MediaPipe framework.

Your contributions help in creating a safer training environment and promote injury prevention in the field of sports and athletics.

RESULTS:


![image](https://github.com/BraulioAlejandroNavarreteHorta/WeightliftingTechniqueAnalysis/assets/133619100/a4b9be96-2321-4a96-8d0a-3f4fc546e6ca)


![image](https://github.com/BraulioAlejandroNavarreteHorta/WeightliftingTechniqueAnalysis/assets/133619100/910a4378-ff6c-4b7b-bdce-fdedee774ee1)

