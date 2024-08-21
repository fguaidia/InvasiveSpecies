# Invasive Species in Colombia Webpage

This project is a simple webpage that displays information about invasive species in Colombia using data from the [API Colombia Invasive Species](https://api-colombia.com/). Each invasive species is presented in Bootstrap-styled cards, and the webpage features dynamic content, including a carousel for species with multiple images and a toggle button for showing or hiding the impact and management details.

## Features

- **Dynamic Content:** Fetches and displays data from the API.
- **Responsive Design:** Built using Bootstrap to ensure the webpage is fully responsive across different screen sizes.
- **Card Layout:** Each invasive species is displayed in a Bootstrap card, with images, names, scientific names, and other relevant details.
- **Toggle Button:** Allows users to show or hide detailed information about each species, such as impact and management methods.

## Technologies Used

- **HTML5**
- **CSS3 (Bootstrap)**
- **JavaScript (Vanilla)**
- **Bootstrap 4.5**
- **API:** [API Colombia Invasive Species](https://api-colombia.com/api/v1/Invasivespecie)

## Setup and Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/invasive-species-webpage.git
    ```

2. Open the `index.html` file in your browser:
    - No server setup is needed. Just open the file directly in your browser.

3. The webpage will automatically fetch and display the list of invasive species in Colombia.

## How It Works

- The webpage makes a GET request to the API and dynamically generates Bootstrap cards for each invasive species.
- Each card includes:
  - An image or an image carousel if multiple images are available.
  - The species' name, scientific name, and common names.
  - Toggle buttons to show or hide the species' impact on the ecosystem and its management recommendations.
  - Risk level information is also displayed.

## Acknowledgements

This project was created with the help of **ChatGPT** by OpenAI. 
