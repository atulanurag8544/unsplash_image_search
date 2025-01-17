

# Image Search and Editor Application

## Overview
This application allows users to search for images via a free image API, edit them by adding captions and shapes, and download the modified images. The tool uses `fabric.js` for canvas manipulation and provides an intuitive interface for interacting with images.

## Features
- **Search Functionality:** Search for images using a free image API (e.g., Unsplash, Pixabay, or Pexels).
- **Canvas Editor:**
  - Add text layers (editable and resizable).
  - Add shapes like Circle, Rectangle, and Triangle.
  - Drag, resize, and reposition elements on the canvas.
- **Download Modified Images:** Save the edited image to your local system.
- **Layer Logging:** Maintain an array of all canvas elements for debugging and transparency.
- **Error Handling:** Proper validation and feedback for user inputs and API interactions.

## Technical Stack
- **Frontend:** HTML, CSS, JavaScript
- **Canvas Manipulation:** Fabric.js
- **Image API Integration:** Any free image API (e.g., Pixabay, Pexels)
- **Deployment Platform:** CodeSandbox, CodePen, or similar.

## Setup Instructions

### Clone the Repository:
```bash
git clone https://github.com/your-username/image-editor-app.git
cd image-editor-app
```

### Install Dependencies:
No additional dependencies are required. Simply open the `index.html` file in a browser to run the application.

### Set Up API Integration:
Replace the placeholder API key in the `script.js` file with your API key from the chosen free image API.

Example for Pixabay:
```javascript
const API_KEY = 'YOUR_PIXABAY_API_KEY';
const API_URL = `https://pixabay.com/api/?key=${API_KEY}&q=`;
```

### Run the Application:
Open the `index.html` file in your browser to launch the app.

## How to Use

### Search for Images:
- Enter a query in the search bar and click "Search" to fetch images.
- Click "Add Captions" on a desired image to load it onto the canvas.

### Edit the Image:
- Use the tools provided to add text and shapes.
- Drag and resize elements as needed.

### Download the Edited Image:
- Click the "Download" button to save the modified image.

## File Structure
```
image-editor-app/
├── index.html        # Main HTML file
├── styles.css        # Styling for the application
├── script.js         # JavaScript logic
└── README.md         # Documentation
```

## Deployment
The app can be deployed on platforms like CodeSandbox or CodePen for easy sharing and access.

## Steps to Run This Application

1. Add your Unsplash API key in the `.env` file.
2. Execute the following commands:

   ```bash
   npm install
   npm run dev
   ```

   Or, if you are using Yarn:

   ```bash
   yarn install
   yarn run dev
   ```

3. Open the application in your browser.

## License
This project is open-source and available under the MIT License.



