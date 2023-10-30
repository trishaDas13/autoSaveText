# autoSaveText

##hoisting link : https://trishadas13.github.io/autoSaveText/

<h2>HTML code description:</h2>

 This HTML code defines a web page featuring a real-time character counter. It begins with a clear title, "Real-time Character Counter." Below that, there's a text input area that allows users to input text. It is configured with a column and row setup, with a placeholder "Write your text here..." to guide users. Additionally, it features two buttons: "Clear All," which presumably clears the text area, and a toggle button, which contains an SVG image.

The SVG image appears as a magnifying glass icon, which can be suggestive of a search function. It's worth noting that the actual functionality of these buttons and the character counting is expected to be implemented in the JavaScript file linked at the bottom of the page ("script.js").

This page seems to serve as a simple, user-friendly text editor that provides character counting and perhaps other functionalities. It can be a useful tool for tasks like word limits, character limits, or content editing.

<h2>CSS code description:</h2>

✔ Font Import: It imports the "Comic Neue" font from Google Fonts.

✔ Universal Reset: The * selector is used to reset margins, paddings, and set the box-sizing to border-box to ensure consistent styling across elements.

✔ Body Styles: The body element is set to occupy the full viewport width and height and centered using justify-content and align-items. The background color is a light pinkish color, and the font-family "Comic Neue" is applied with italic style.

✔ h1 Styles: This styles the h1 element. It sets the font weight and text alignment.

✔ Container Styles: The .container class styles the main container. It includes padding, box-shadow, border-radius, and a background color. It's a flex container with a column direction and a gap between child elements.

✔ Text Area Styles: The textarea elements inside the container are styled to have padding, font size, no resize behavior, font weight, no outline, border-radius, a dotted black border, and a background image. The image is applied as the background, set to no-repeat, cover, and centered.

✔ Button Styles: The button element is styled with padding, border-radius, no border, font family, font style, font size, background color, a dotted black border, and a box-shadow. On hover, the button's box-shadow and background color change to give a visual effect.

✔ Media Query for Small Screens: When the screen width is below 540px, the container's height and width are set to 100vh and 100% respectively. This makes the container take up the entire viewport height and width on smaller screens.

✔ Dark Mode Toggle Button: The #toggle ID styles a toggle button for switching between light and dark modes. It has a transparent background, no border, no outline, and a cursor pointer.

✔ Dark Mode Styles: The .dark class is used to define styles for the dark mode. It sets a background image as a linear gradient, changing the background from a light pinkish color to a gradient from gray to greenish color. The container's background color changes to a yellowish color in dark mode.

<h2>JS code description:</h2>

✔ Clear Textarea:

A button (btn) is provided, and when it is clicked, it clears the content of a textarea (text) on the web page.
Autosave Textarea Content:

✔ When the user types or makes changes in the textarea, the content is automatically saved in the browser's local storage. This allows the text to be retained even if the user refreshes the page or closes the browser. The content is associated with the key "name" in the local storage.
Restore Textarea Content:

✔ When the page is loaded or refreshed, the code checks whether there is content associated with the "name" key in local storage. If content is found, it is loaded into the textarea, restoring the user's previous input.
Dark and Light Theme Toggle:

✔ There is a button or element (probably referred to as toggle) that allows the user to toggle between dark and light themes for the web page.
When the button is clicked, it toggles the class "dark" on the document.body element. This class is likely associated with CSS rules that control the appearance of the web page.
The code also updates the button's content (probably an SVG icon) to indicate the current theme. If the page is in dark mode, the icon suggests switching to light mode, and vice versa.

<h2>Summary</h2>
It's important to note that some elements in the code (e.g., toggle) are referenced but not defined in the provided snippet. To fully implement this code, you would need to ensure that these elements are correctly selected in your HTML document and that the CSS styles for the dark and light themes are properly defined. Additionally, any required HTML and CSS code to complement this JavaScript functionality is not included in the provided snippet.

<h2>UI:</h2>

![image](https://github.com/trishaDas13/autoSaveText/assets/126088849/1dc2e83f-95f1-46d7-b033-276fb29d94b5)
