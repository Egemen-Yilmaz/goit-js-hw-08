🏞️ Image Gallery Project (with basicLightbox)
This project is a modern image gallery application that dynamically renders images from a data array. It features interactive functionality to display a magnified version of an image in a modal window upon click, using the basicLightbox library.

🌟 Features
Dynamic Markup Generation: Gallery items are automatically created from the JavaScript data array (images).

CSS Grid Layout: The gallery is styled using a clean, responsive CSS Grid layout.

Event Delegation: A single event listener is used on the gallery container for improved performance and scalability.

Modal Window: The magnified version of the clicked image is displayed within a modal provided by the basicLightbox library.

Keyboard Accessibility: The modal can be closed by pressing the Escape key, and the keydown event listener is correctly detached when the modal closes (ensuring clean memory management).

Hover Effect: A subtle visual enhancement is added using transform: scale(1.04) to provide a smooth scaling effect when hovering over an image.

🛠️ Technologies
HTML5

CSS3 (Includes CSS Grid and transform for effects)

JavaScript (ES6+)

basicLightbox: A lightweight and powerful library for creating modals.

🚀 Setup and Launch
Follow these steps to run the project locally:

Clone the Repository:

Bash
git clone [YOUR_PROJECT_REPO_ADDRESS]
cd [your-project-folder-name]
File Structure: The project has a clean file structure:

.
├── index.html         # Main HTML file
└── js/
    └── gallery.js     # All gallery creation and interaction logic
└── css/
    └── style.css      # Gallery styles (Optional: If using a separate CSS file)
Run the Application: Simply open the index.html file in your web browser (by double-clicking it or using a Live Server extension).

📌 Usage
View the images displayed in the gallery layout.

Hover over any image to see the smooth, slightly magnified effect.

Click on an image to open the larger version in a modal window.

To close the modal:

Click on the dark overlay area outside the image.

Press the Escape key on your keyboard.

📜 License
This project is currently unlicensed.