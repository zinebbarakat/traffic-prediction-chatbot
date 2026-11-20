# Traffic Prediction Chatbot

An LLM-powered chatbot that predicts traffic levels on **Calle de la Castellana, Madrid**, from natural-language questions. It combines **live weather data** with **machine learning classification** to estimate traffic conditions.

> Team project (4 students), developed during my Computer Engineering degree at Universidad Europea de Madrid. The source code lives in a private university repository and is available on request.

## What it does
- Understands questions in natural language (for example, "Will there be heavy traffic on Castellana tomorrow morning?") using an LLM (Gemini API).
- Fetches live weather data from the Open-Meteo API.
- Predicts the traffic level with ML classification models (KNN, K-Means).
- Provides a full-stack web interface built with Reflex, deployed on a virtual machine.

## How it works
1. The user asks a question in natural language.
2. The LLM extracts the relevant parameters (time, day, conditions).
3. The weather module retrieves live conditions from Open-Meteo.
4. The trained model predicts the traffic level.
5. The result is returned to the user through the chat interface.

## Tech stack
**Python** · **Gemini API** · **scikit-learn (KNN, K-Means)** · **Open-Meteo API** · **Reflex** · Virtual machine deployment · Git/GitHub

## My role
I worked on this project as part of a team of 4, collaborating across the full stack: data and ML, LLM integration, backend and interface.

## What I learned
- Integrating an LLM into an application as a component of a larger pipeline
- Combining external APIs with trained ML models
- Collaborating in a team with Git: branches, pull requests and merge conflicts
- Building and deploying a full-stack application end to end
