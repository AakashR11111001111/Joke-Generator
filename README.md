# Jokes Generator 😂

A fun web application that generates random jokes with a refreshing twist. Users can fetch new jokes at the click of a button and toggle between light and dark modes for a different look.

## Live Demo
Check out the project live [here](https://aakashr11111001111.github.io/Joke-Generator/)!

## Features
- **Random Dad Jokes**: Fetches a new joke with each button click using an external API.
- **Dark Mode**: Toggle between light and dark themes to enhance readability and add style.
- **Dynamic SVG Icons**: Refresh and dark mode buttons include animated SVG icons.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Dad-Jokes-Generator.git
    ```
2. **Navigate to the project folder**:
    ```bash
    cd Dad-Jokes-Generator
    ```
3. **Open `index.html` in your browser** to view the project locally.

## Usage
1. Click on the **Refresh** button to get a new joke.
2. Use the **Dark Mode** button to toggle between light and dark themes.

## Code Overview

- **HTML**: Basic structure including buttons and container for jokes.
- **CSS**: Styling for light and dark modes with transitions.
- **JavaScript**: 
    - Fetches dad jokes from the API-Ninjas jokes API.
    - Handles dark mode toggle and dynamic SVG color changes.
    - Adds error handling for unsuccessful API requests.

## API Used
The project uses the [API-Ninjas Dad Jokes API](https://api-ninjas.com/) to fetch random jokes.

**API Key**: Replace the `X-Api-Key` in `script.js` with your own API key for it to work correctly.

```javascript
var opt = {
    headers: { 'X-Api-Key': 'YOUR_API_KEY_HERE' },
    method: 'GET',
}
