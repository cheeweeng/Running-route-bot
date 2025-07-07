# Project Overview  
This project was born out of my love for running and learning and applying new technologies as I explore the world of AI workflow and automation.  
The Running Route bot is a Telegram bot that generates personalized running routes based on user inputs like distance and run type (e.g. easy, tempo, interval). It integrates real-time weather data and provides motivational messages and Google Maps links for navigation.

Built using Zapier, Telegram API, OpenWeatherMap API, and custom JavaScript, this project showcases automation, API integration, and user-friendly design.
* Attribution:  The custom JavaScript found in two nodes in the automation workflow were created by Claude.ai (Sonnet4)

# Key Features  
* Parses natural language requests (e.g., "5km easy run")
* Fetches real-time weather data via OpenWeatherMap API  
* Provides motivational message
* Generates circular running routes via OpenRouteService with Google Maps links
* Handles multiple run types (easy, tempo, interval, recovery)

## Video Demo (unmute the video for sound):
[Video demo](https://github.com/user-attachments/assets/f09c066d-1d63-4ba7-8c22-5a7e5621001e)

## Challenges & Solutions  
Challenge: Lack of knowledge in JavaScripting  
Solution: Effective prompting of Claude.ai and iteratively improving the output via many trials and errors.  

Challenge: Generating realistic running routes.  
Solution: Using OpenRouteService API and prompting Claude.ai iteratively to finalise the JavaScript to implemented a circular route algorithm.  

Challenge: Handling API rate limits.  
Solution: Optimized API calls and used Zapier’s free tier effectively.  

Challenge: The JavaScript code for parsing messages and generating routes can be tricky to debug  
Solution: Prompting Claude.ai iteratively with text and screenshots until the bug was found and a satisfactory output was achieved.
