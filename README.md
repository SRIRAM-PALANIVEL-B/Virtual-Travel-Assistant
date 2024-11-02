# Virtual-Travel-Assistant


# TravelScanner ✈️

TravelScanner is an interactive travel assistant chatbot built using Streamlit and the OpenAI GPT model. It helps users plan their trips by providing assistance with booking flights, hotels, rental cars, offering destination information, travel tips, and more.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)


## Features
- **Booking Assistance**: Get help with booking flights, hotels, and rental cars.
- **Destination Information**: Learn about popular travel destinations, attractions, and local culture.
- **Weather Updates**: Access current weather conditions and forecasts for your travel destinations.
- **Travel Tips**: Receive practical tips on packing, visa requirements, and local customs.
- **Customer Support**: Address inquiries related to bookings, cancellations, and refunds.

## Technologies Used
- **Python**: The primary programming language for development.
- **Streamlit**: A framework for building web applications.
- **OpenAI API**: Provides access to the GPT-4 model for natural language processing.
- **dotenv**: Manages environment variables for secure configuration.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/travelscanner.git
   cd travelscanner


# Create a virtual environment (optional but recommended):

    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`


# Install the required packages:

    pip install -r requirements.txt

# Create a .env file in the root directory and add your OpenAI API key:

    OPENAI_API_KEY=your_api_key_here


# Usage

To run the application, execute the following command:

    streamlit run app.py
    
Open your web browser and navigate to http://localhost:8501 to access the TravelScanner app.

# Environment Variables

To use the OpenAI API, you need to set the following environment variable:
- OPENAI_API_KEY: Your OpenAI API key.
  
Make sure to keep this key private and secure.



![Project Logo](logo.png)
