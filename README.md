# Responsive Image Gallery

This project is a responsive image gallery showcasing a collection of images with a sleek, interactive user interface. It features a main image display area with navigation controls and an integrated, responsive carousel for easy browsing of thumbnails. The gallery is built using fundamental web technologies complemented by popular jQuery plugins to enhance user experience and responsiveness.

The project appears to be a demo or example originally created by [Codrops](https://tympanus.net/codrops/).

## About the Project

This Responsive Image Gallery is designed to provide an engaging way to view images on various screen sizes.

**Key Features:**

*   **Responsive Design:** Adapts seamlessly to different screen resolutions, from desktops to mobile devices.
*   **Main Image Viewer:** Displays a large version of the selected image, complete with previous/next navigation.
*   **Image Carousel (Elastislide):** A horizontally scrollable thumbnail carousel at the bottom allows for quick navigation and selection of images.
*   **Dynamic Loading:** Images are loaded dynamically, with a loading indicator for a smooth experience.
*   **jQuery Powered:** Leverages jQuery and several specialized plugins (Elastislide, Easing, jTmpl) for smooth animations and robust functionality.

**Technologies Used:**

*   **HTML5:** Structures the content and layout of the gallery.
*   **CSS3:** Provides styling for a modern look, including responsive layouts and visual effects (`demo.css`, `style.css`, `elastislide.css`, `reset.css`). Utilizes Google Fonts for typography.
*   **JavaScript (ES5+):** Implements interactive behaviors and custom gallery logic.
*   **jQuery:** The core JavaScript library facilitating DOM manipulation, event handling, and AJAX.
*   **jQuery Elastislide Plugin:** Powers the responsive image carousel.
*   **jQuery Easing Plugin:** Adds advanced easing functions for smoother animations.
*   **jQuery Tmpl Plugin:** Used for client-side templating to render image content dynamically.
*   **ImagesLoaded Plugin:** Ensures images are fully loaded before executing callbacks, preventing layout shifts.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You only need a modern web browser (e.g., Chrome, Firefox, Safari, Edge) to view this project.

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/your-username/responsive-image-gallery.git
    cd responsive-image-gallery
    
    *(Note: Replace `https://github.com/your-username/responsive-image-gallery.git` with the actual repository URL if available, otherwise assume local copy).*

2.  **Open in your browser:**
    Navigate to the project directory and open the `gallery.html` file directly in your web browser.
    bash
    # Example for Linux/macOS
    open gallery.html
    # Example for Windows
    start gallery.html
    
    Alternatively, if you use a code editor like VS Code, you can use an extension like "Live Server" to serve the `gallery.html` file, which is often recommended for development to ensure proper path resolution and avoid browser security restrictions for local files.

## Usage

Once `gallery.html` is open in your browser, you will see the image gallery.

*   **View Main Image:** The largest image in the center is the currently selected image.
*   **Navigate Main Images:** Use the "Previous Image" and "Next Image" arrows that appear on the left and right sides of the main image to move through the gallery.
*   **Browse Thumbnails:** Below the main image, there is a carousel of thumbnail images. Click on any thumbnail to display that image in the main viewer.
*   **Carousel Navigation:** The thumbnail carousel itself has small arrows on its sides to scroll through the available thumbnails if there are more than can fit on the screen.
*   **View Modes:** The top right corner of the main image section might offer options to switch between different view modes (e.g., full view, thumbnail grid), depending on the implementation in `gallery.js` and `style.css`. *(Based on `.rg-view` classes, there are typically options for "full" and "thumbs" views).*
