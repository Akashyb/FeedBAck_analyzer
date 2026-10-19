# 📝 Customer Feedback Analyzer

## Overview

The **Customer Feedback Analyzer** is a Generative AI-powered application that automatically analyzes customer reviews and converts unstructured feedback into meaningful business insights. It uses Google Gemini AI to identify customer sentiment, assign satisfaction scores, and determine the main topic of each review.

Built with **Python, FastAPI, Streamlit, and SQLite**, the application provides an interactive dashboard where business owners can analyze multiple reviews, view summary statistics, and store results for future reference.

## ✨ Key Features

- **Sentiment Analysis:** Classifies reviews as positive, negative, or neutral.
- **Satisfaction Scoring:** Assigns a score from 1 to 5.
- **Theme Identification:** Identifies the main topic, such as delivery, price, service, or quality.
- **Batch Processing:** Analyzes multiple customer reviews in one session.
- **Interactive Dashboard:** Displays individual results, average satisfaction scores, positive review percentages, and common feedback themes.
- **Database Integration:** Stores analyzed reviews in SQLite and retrieves historical records.
- **REST API:** Uses FastAPI to connect the frontend with the AI analysis service.

## 🛠️ Technology Stack

- Python
- Google Gemini AI
- FastAPI
- Streamlit
- SQLite
- Pydantic
- Requests
- python-dotenv

## 🏗️ Architecture

1. **Streamlit (`app.py`):** Accepts customer reviews and displays analysis results.
2. **FastAPI (`api.py`):** Receives reviews through the `/analyze` endpoint and communicates with Gemini AI.
3. **Gemini AI:** Performs sentiment classification, satisfaction scoring, and theme identification.
4. **SQLite (`database.py`):** Stores analyzed reviews and retrieves saved history.

## 🎯 Use Cases

This application can help restaurants, retail stores, e-commerce businesses, and service providers understand customer opinions, identify recurring issues, and improve customer satisfaction.

## 🚀 Future Enhancements

- Multilingual review analysis
- Real-time feedback monitoring
- Advanced visualizations and trend analysis
- Integration with business platforms
- Support for larger datasets

## 💡 Objective

To transform customer feedback into actionable insights using Generative AI, helping businesses make informed decisions and deliver better customer experiences.
