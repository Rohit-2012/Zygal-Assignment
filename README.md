# ZYGAL Assignment

This web application is a simple HTML5 Canvas-based tool that allows users to draw a character (in this case, the Indian Rupee symbol "₹") on a canvas and then download the pixel color data of the canvas in hexadecimal format. The pixel color data is represented as a 16x34 matrix, where each cell corresponds to a pixel on the canvas and contains its color in hexadecimal format.

## Features

- **Drawing the Character:** Upon loading the web page, the canvas will display the Indian Rupee symbol "₹" drawn in blue color on a white background.
- **Downloading Pixel Color Data:** To download the pixel color data, follow these steps:
  1.  Click on the "Download" button below the canvas.
  2.  This will trigger the process of converting the canvas pixel color data into hexadecimal format.
  3.  The converted data will be downloaded as a text file named "hex_data".
- **Matrix Format of Hexadecimal Data:** The downloaded text file will contain the pixel color data in a 16x34 matrix format. Each row represents a row of pixels on the canvas, and each cell in a row corresponds to a pixel's color in hexadecimal format.

## Tech Stacks

- HTML
- CSS
- Javascript

## Note

- The web application is built using HTML, CSS, and JavaScript.
- The application has been tested on modern web browsers with support for HTML5 Canvas.
- The "₹" character is drawn using the fillText method of the HTML5 Canvas API.
- The pixel color data is extracted using the getImageData method, and each color is converted into a hexadecimal representation.
- The converted hexadecimal data is then formatted into a 16x34 matrix before being downloaded as a text file.

## Compatibility

The web application should work on most modern web browsers that support HTML5 Canvas and JavaScript.

## Author

The web application was created by Rohit Kirti.

## Contact

If you have any questions or feedback regarding the application, you can reach out to the author at rohit.kirti1219@gmail.com.

## Deployment Site Link

Open https://zygal-assignment.netlify.app/ in your browser to view the application.
