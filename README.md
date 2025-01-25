# White Noise Image Generator

This is a simple web-based tool that allows you to generate images simulating white noise. You can customize the image by setting the number of columns, rows, square size, color mode, and bias.

## Features

-   **Customizable Dimensions:** Set the number of columns and rows to control the image's size.
-   **Adjustable Square Size:**  Modify the size of the squares that make up the white noise pattern.
-   **Various Color Modes:**
    -   Monochrome: Generates a grayscale image.
    -   Red, Blue, Green: Generates an image using only the selected color.
    -   Gradient 2-color: Creates a gradient between two chosen colors.
    -  Gradient 3-5 color: Creates a gradient with a random 3-5 color gradient
-   **Bias Control:**  Adjust the overall lightness or darkness of the generated image with bias options.
-   **Downloadable Images:** Download the generated image as a PNG file.

## How to Use

1.  **Set Dimensions:**
    -   Enter the desired number of columns and rows for your image.
    -   Input the size of the individual squares (in pixels).
2.  **Select Color Mode:** Choose the type of color you want for the noise.
    -   If "Gradient 2-color" is selected, pick the start and end colors using the color pickers.
3.  **Set Bias:** Choose a bias to make the image generally lighter or darker.
4.  **Generate:** Click the "Generate" button to create the white noise image.
5. **Download:** Click the "Download" button to save the image locally
6.  The generated image will be displayed on the canvas.

## Technology

-   **HTML:**  Provides the structure of the web page.
-   **CSS:**  Styles the look and feel of the page.
-   **JavaScript:** Handles user interactions, generates the white noise, and manages image display.

## Getting Started

1.  Clone the repository to your local machine.
2.  Open the `index.html` file in your web browser.

## Example
![{FB42EDD0-BAC1-4F99-B2D6-338171E0CED6}](https://github.com/user-attachments/assets/59474afc-0c1d-4c81-8d07-cd2aed169322)


## Warning

Please be aware that generating very large images (with many pixels) may cause your browser to freeze or crash. A warning message will appear if you're about to generate a large image.

## Code Author
- [Sl1dee36](https://github.com/SL1dee36)
