# Explainable AI for Phishing Email Detection

## About the Project

For my final-year Computing project, I am working on a system that can detect phishing emails using machine learning.

Phishing emails are fake or misleading emails that try to trick people into giving away personal information, such as passwords or bank details. Some of these emails also encourage users to click suspicious links or download harmful files.

The main idea behind this project is not just to detect whether an email looks like phishing, but also to show why the system has made that decision. This will help users understand which parts of an email might be suspicious.

## What I Want to Achieve

I plan to build a small web application where users can enter an email and check whether it is likely to be phishing or legitimate.

I also want to compare different machine learning models to see how well they perform. Along with the prediction, the system will try to explain which words or features influenced the result.

The main things I plan to do are:

- Research phishing emails and existing detection methods.
- Find a suitable dataset containing phishing and legitimate emails.
- Clean and prepare the email data for training.
- Use TF-IDF to process the email text.
- Train and compare Logistic Regression, Random Forest and Support Vector Machine (SVM) models.
- Use LIME to explain individual predictions.
- Compare the models using accuracy, precision, recall and F1-score.
- Build a simple web application to demonstrate the final system.

## Tools and Technologies

These are the main tools and technologies I currently plan to use:

- **Python** – main programming language.
- **Scikit-learn** – for building and testing machine learning models.
- **Pandas and NumPy** – for handling and preparing the data.
- **TF-IDF** – for converting email text into numerical features.
- **LIME** – for explaining the model's predictions.
- **Flask** – for developing the web application.
- **HTML and CSS** – for designing the application interface.
- **Jupyter Notebook and VS Code** – for development and testing.
- **GitHub** – for managing and storing the project code.

## Expected Final Outcome

By the end of the project, I aim to have a working web application where a user can enter an email and receive a result showing whether it is likely to be phishing or legitimate.

The application will also provide a simple explanation of the prediction, such as highlighting words that influenced the result.

I will also have a comparison of the machine learning models to discuss which performed better and which provided more understandable results.

## Planned Folder Structure

```text
Explainable-AI-Phishing-Detection/
│
├── README.md
├── data/
├── notebooks/
├── src/
├── models/
├── web_app/
├── tests/
└── requirements.txt
```

I will update the folders and add files as the project develops.

## Project Supervisor

**Supervisor:** Dr. Hai-Van Dang

## Current Progress

At the moment, I am working on the project initiation stage. This includes researching the topic, reviewing existing work, choosing a suitable dataset, planning the development stages and setting up the development environment.

I will update this repository as I make progress throughout the project.
