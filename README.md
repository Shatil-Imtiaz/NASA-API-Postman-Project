# NASA-API-Postman-Project

This project demonstrates how to interact with NASA's public APIs using Postman. It covers the retrieval of Mars Rover photos and the Astronomy Picture of the Day (APOD).
🚀 Project Overview

Curiosity is a Mars rover launched by NASA to explore the Gale Crater on Mars as part of the Mars Science Laboratory (MSL) mission. Using NASA's API, we can retrieve images captured by Curiosity and other rovers.

This Postman project includes:

    📸 Fetching Mars Rover photos taken by Curiosity on:
        Sol 1 (Martian solar day)
        Earth date: 2022-10-28
    🌌 Getting the Astronomy Picture of the Day (APOD)

🔧 APIs Used

    Mars Rover Photos API:
    https://api.nasa.gov/mars-photos/api/v1/rovers/curiosity/photos

    Astronomy Picture of the Day API:
    https://api.nasa.gov/planetary/apod

🔐 Requirements

To use these APIs, you need a NASA API Key.
How to get an API Key:

    Go to https://api.nasa.gov
    Sign up using your email address
    Use the generated api_key in your requests

🧪 Example Endpoints

    Get photos taken on Sol 1: GET https://api.nasa.gov/mars-photos/api/v1/rovers/curiosity/photos?sol=1&api_key=YOUR_API_KEY

    Get photos taken on Earth date 2022-10-28: GET https://api.nasa.gov/mars-photos/api/v1/rovers/curiosity/photos?earth_date=2022-10-28&api_key=YOUR_API_KEY

3.Get Astronomy Picture of the Day: GET https://api.nasa.gov/planetary/apod?api_key=YOUR_API_KEY
