# **Turkey City Guessing Game**

## Game Overview

The Turkey City Guessing Game is designed to help players identify Turkey’s 81 cities using a series of four clues for each city. Based on the clues provided, the player must guess the correct city and select it on a map of Turkey. Each city is asked only once, and the game continues until all cities are correctly identified.

## Requirements

### 1. General Game Flow

	•	The player is presented with four clues for a randomly selected city in Turkey.
	•	Using these clues, the player guesses the city.
	•	When the player correctly guesses the city, it is marked on the map and will not be asked again.
	•	The game continues until all cities have been guessed correctly.

### 2. Clue System

#### Each city has four distinct clues:

	•	License Plate Code: The city’s unique license plate code.
	•	Most Famous Dish: The city’s most well-known traditional dish.
	•	Most Famous Historical Site: The city’s most famous historical landmark.
	•	Unique Characteristic: A defining characteristic that sets the city apart from others.

### 3. Map Interface

	•	The game should display a simple map of Turkey with only the regions of each city shown.
	•	The map highlights the area of each city without detailed borders.
	•	When a city is guessed correctly, its area on the map is marked (e.g., with a color change).

### 4. Question Management

	•	Each city is only asked once and does not repeat after being correctly guessed.
	•	Each new city question is randomly chosen from the remaining unguessed cities.
	•	The game continues until the player has guessed all cities correctly.

### 5. Game End and Scoring

	•	The game ends once the player has successfully identified all cities.
	•	Upon completion, the game can display performance metrics, such as the number of attempts or time taken to finish.

### 6. User Interface

	•	The game screen should feature a simple map view alongside an area displaying the clues.
	•	The game interface should be clean and easy to understand.

### 7. Developer Requirements

	•	The game should be developed using HTML, CSS, and JavaScript.
	•	The map can be displayed using SVG or Canvas API.
	•	A static image or SVG-based map of Turkey’s cities can be used for city selection.
