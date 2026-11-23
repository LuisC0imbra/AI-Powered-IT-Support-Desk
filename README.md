
# AI-Powered IT Support Desk

An AI-powered IT Support Desk developed using **Python, Google Gemini, Pandas, and SQLite** to automate ticket classification, predict priorities, generate responses, and evaluate AI prediction accuracy.

## Project Overview

IT support teams handle a wide range of technical requests, each requiring appropriate classification and prioritization.

This project explores how **Generative AI** can automate repetitive support tasks and improve the efficiency of IT ticket management.

The solution combines data analysis, object-oriented programming, database management, and AI integration to build an intelligent support ticket processing workflow.

## Project Objectives

- Clean and prepare IT support ticket data.
- Analyze ticket categories, priorities, and customer ratings.
- Automatically classify support tickets using Google Gemini.
- Predict ticket priority based on ticket descriptions.
- Generate AI-assisted responses to support requests.
- Evaluate AI predictions against existing ticket labels.
- Explore prompt engineering techniques to improve accuracy.
- Store and manage ticket information using SQLite.

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core programming language |
| Pandas | Data cleaning and analysis |
| Matplotlib | Data visualization |
| Google Gemini API | AI classification and response generation |
| SQLite | Database management |
| Google Colab | Development environment |

## Project Workflow

### 1. Data Preparation

The dataset is imported and processed using Pandas.

Main activities include:

- Exploring the dataset structure.
- Identifying and handling missing values.
- Cleaning ticket information.
- Preparing data for AI processing.

### 2. Exploratory Data Analysis (EDA)

Exploratory analysis is performed to identify patterns in IT support requests.

The analysis includes:

- Ticket distribution by category.
- Ticket distribution by priority.
- Customer rating distribution.
- Average customer ratings by category.
- Data visualization using Matplotlib.

### 3. AI-Powered Ticket Classification

Google Gemini is integrated into the Python workflow to automatically classify incoming support tickets.

The AI analyzes ticket descriptions and predicts the most appropriate category.

Predictions are compared with the original dataset labels to evaluate classification accuracy.

### 4. Priority Prediction

Gemini is also used to predict ticket priority based on the content of each support request.

This functionality demonstrates how AI can assist IT teams in identifying requests requiring greater attention.

### 5. Prompt Engineering

Different prompting approaches are explored to evaluate their impact on classification performance.

The project investigates whether providing additional context and representative examples improves prediction accuracy.

### 6. AI-Generated Responses

Google Gemini generates responses to support requests, demonstrating how Generative AI can assist support teams with customer communication.

### 7. SQLite Database Integration

SQLite is used to store and manage ticket information and AI-generated results.

The database supports structured data storage and retrieval.

## Object-Oriented Programming

The project applies Object-Oriented Programming (OOP) concepts to organize its functionality.

Key concepts include:

- Classes and objects.
- Inheritance.
- Constructors (`__init__`).
- Method overriding.
- Reusable methods.

These concepts help separate ticket management, database operations, and AI functionality.

## AI Evaluation

AI predictions are compared against the original ticket labels to evaluate classification performance.

The evaluation focuses on:

- Category classification accuracy.
- Priority prediction accuracy.
- Comparison between initial and improved prompts.
- Identification of potential improvements.

## Key Skills Demonstrated

- Python programming
- Object-Oriented Programming (OOP)
- Data cleaning and preprocessing
- Exploratory Data Analysis
- Generative AI integration
- Prompt engineering
- AI classification and evaluation
- SQL and database management
- Workflow automation

## Future Improvements

Potential improvements include:

- Developing an interactive dashboard for ticket monitoring.
- Implementing automatic ticket routing.
- Testing additional AI models.
- Expanding classification to larger datasets.
- Deploying the solution as a web application.

## About This Project

This project was developed as part of the **Python for Data & AI** course.

Its purpose is to apply Python programming, data analysis, database management, and Generative AI concepts to a practical IT support use case.

The project demonstrates how traditional data processing techniques can be combined with modern AI capabilities to support operational efficiency.

---

**Author:** [Luis Coimbra](https://github.com/LuisC0imbra)
