# pay-per-click-ad-fraud-detection
Overview

Developed a machine learning pipeline to detect fraudulent ad clicks in a dataset exceeding 58 million records from TalkingData, optimizing memory usage with efficient data types (e.g., uint32, uint16).

Features and Implementation

Engineered advanced features including time-to-next-click, interaction frequency encodings (e.g., IP-app-OS, app-channel), and temporal attributes (day, hour, minute) to capture fraud patterns.
Visualized class imbalance (fraud rate ~0.2%) and feature distributions (e.g., log-transformed IP frequency) using Seaborn and Matplotlib, revealing insights into bot activity and temporal trends.
Applied StandardScaler for numerical feature scaling and RandomUnderSampler to address severe class imbalance (1:2 ratio), preparing balanced data for training models like LightGBM or XGBoost.

Purpose and Impact

Aimed to enhance ad fraud detection accuracy by preprocessing and analyzing large-scale click data, providing a robust dataset for predictive modeling.
Contributed to identifying bot-driven activities, supporting improved security and efficiency in online advertising ecosystems.

Technologies Used

Programming Language: Python
Libraries: Pandas, Scikit-learn, Seaborn, Matplotlib
Dataset: TalkingData (subset of 58M+ records)

Getting Started

Clone the repository and install required dependencies:
bashpip install pandas scikit-learn seaborn matplotlib

Load the dataset (e.g., train.csv and test_supplement.csv) and run the provided scripts for data processing and visualization.

Future Improvements

Integrate additional machine learning models (e.g., LightGBM, XGBoost) for enhanced prediction accuracy.
Expand feature engineering to include more temporal and behavioral patterns.

Instructions:

Save this text in a file named README.md in your project directory.
The content uses Markdown syntax, which is widely supported on GitHub and other platforms.
Adjust the "Getting Started" section if you have specific file paths or additional setup steps.
Feel free to add sections like "License" or "Contributors" if applicable.

This README mirrors the concise, bullet-point style of your resume image while providing a professional overview of your project. Let me know if you'd like to tweak it further!
