# Automated Customer Complaint Management System

## Description

Efficiently categorizing customer complaints is a critical task for organizations to streamline issue resolution and enhance customer satisfaction. Manually handling complaints is time-intensive and prone to errors, especially with large datasets or complex complaint descriptions.

This project addresses this challenge by developing an automated system that preprocesses textual complaints, leverages **DistilBERT embeddings** for feature extraction, and classifies them using a **Gradient Boosting Classifier**. Additionally, the system provides category recommendations based on semantic similarity, enabling accurate categorization and aiding in faster resolution of customer grievances.

---

## Installation and Configuration Guide

### 1. Clone the Repository
Clone the project repository to your local machine:
```bash
git clone https://github.com/your-username/complaint-categorization-system.git
cd complaint-categorization-system
```
### 2. Install Dependencies
Set up the Python environment and install the required dependencies:
```bash
pip install -r requirements.txt
```
### 3. Download Pre-trained DistilBERT Weights
The required tokenizer and model weights for DistilBERT are automatically downloaded when the program is executed, using the transformers library. 
### 4. Run the Program
Execute the main script to test the system using the sample data provided:
```bash
python main.py
```

