# Photo-Gallery
# COA (Collection of Animals)

## Description
This project is a simple web page that displays a collection of animals along with their respective locations. Each animal card includes an image, the animal's name, and the location where it can be found. There is also a "Know more" link for each animal card, although it currently does not redirect to another page.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)
- [Acknowledgements](#acknowledgements)

## Installation
To view or modify this project, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/bertrandrw/Photo Gallery.git

Navigate to the project Directory


   cd COA


   
Usage


To use or view the project, open the home.html file in any web browser. The webpage displays four animals with their images, names, and locations. When you hover over an animal card, an overlay appears with a "Know more" link.


License


Contact Information
brwogera@gmail.com

Project Link: https://github.com/bertrandrw/Photo-Gallery

Acknowledgements
Images sourced from various free stock image providers.
HTML and CSS templates used as a basis for styling and layout.
GitHub Emoji Cheat Sheet for the arrow icon.


HTML Structure
The HTML file defines a simple web page with a collection of animal cards. Each card contains an image, the animal's name, the location, and a "Know more" link.

Head Section
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>COA</title>
</head>

DOCTYPE: Defines the document type and version of HTML.
html: Sets the language attribute to English.
head: Contains metadata, character set, viewport settings for responsiveness, link to the CSS file, and the page title.


Body Section
html
Copy code
<body>
    <div class="container-wrapper">
        <!-- Individual Animal Container -->
        <div class="container">
            <img src="Fox.jpg" alt="fox" class="image">
            <div class="display">
                <div class="display1">
                    <p>FENNEC FOX</p>
                </div>
                <div class="display2">
                    <span>India</span>
                </div>
            </div>
            <div class="overlay">
                <a href="#">Know more <span class="arrow">&rarr;</span></a>
            </div>
        </div>
        <!-- Repeat similar structure for other animals -->
    </div>
</body>
</html>
body: Contains the main content of the webpage.
container-wrapper: A wrapper for all animal containers.
container: Individual animal container with image, display information, and overlay.
Key Elements
img: Displays the animal image.
display: Container for animal name and location.
overlay: Contains the "Know more" link which appears on hover.
