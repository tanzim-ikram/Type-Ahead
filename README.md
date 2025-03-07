# Type Ahead 👀

Type Ahead is a simple and interactive city and state search tool that provides real-time suggestions based on user input. It fetches data from a remote JSON source and dynamically updates the suggestions as the user types.

## **📸 Preview**  
![Type Ahead Preview](<Type Ahead 1.png>)

## Features
- **Live Search:** Displays city and state matches as you type.
- **Highlighting:** Highlights matched text in results.
- **Population Display:** Shows the population of each matched city.
- **User-Friendly Interface:** Responsive and visually appealing design.

## Technologies Used
- **HTML**: Structure of the webpage.
- **CSS**: Styling for better user experience.
- **JavaScript**: Fetches data, processes user input, and dynamically updates the UI.

## Installation & Usage
```sh
# Clone the repository
git clone https://github.com/tanzim-ikram/Type-Ahead.git

# Navigate to the project directory
cd Type-Ahead

# Open index.html in your browser
```

## How It Works
1. When the user starts typing in the search box, a function searches for matching city or state names in the dataset.
2. Matching results are displayed dynamically below the search box.
3. The typed text is highlighted in the displayed results.
4. The population of each matched city is also shown with formatted numbers.

## API Used
The project fetches city and state data from the following endpoint:
```sh
https://gist.githubusercontent.com/Miserlou/c5cd8364bf9b2420bb29/raw/2bf258763cdddd704f8ffd3ea9a3e81d25e2c6f6/cities.json
```