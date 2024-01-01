# qr-code-component

The HTML code you provided is a basic structure for a web page that seems to showcase a QR code component. Here's a breakdown of what's included in this HTML:

1. **Metadata**: 
   - Character set (`<meta charset="UTF-8" />`): Defines the character encoding for the document.
   - Viewport (`<meta name="viewport" content="width=device-width, initial-scale=1.0" />`): Ensures that the website is displayed correctly on various devices.
   
2. **Stylesheets**: 
   - A custom stylesheet (`<link rel="stylesheet" href="style.css" />`) is linked for styling purposes.
   - A favicon (`<link rel="icon" ... />`) is included for the website's tab.
   - Google Fonts (`<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">`) are imported to use the "Outfit" font in the web page.

3. **Body Content**: 
   - A main container (`<div class="main-container">`) wraps the content of the page.
   - Inside the container, there are two main blocks:
     - **QR Code Block**: This block contains an image (`<img src="images\image-qr-code.png" class="qr-code" />`) displaying a QR code.
     - **Text Block**: This block contains a heading (`<h1>`) and a paragraph (`<p>`). The text encourages users to scan the QR code to visit Frontend Mentor and improve their front-end skills.
   
4. **Attribution**: 
   - At the bottom of the page, there's an attribution section that gives credit to Frontend Mentor for the challenge and allows for adding your name as the coder.

Overall, this HTML structure provides a simple and clean layout to showcase a QR code and some accompanying text. The design and additional styling will be determined by the linked CSS (`style.css`) and any additional styles you might add.



The provided CSS code complements the HTML structure you've shown earlier. Here's a breakdown of the styles you've applied:

1. **Universal Reset (`*`)**:
   - Removes default margins and paddings.
   - Uses the box model to ensure elements behave as expected.
   - Sets the default font to 'Outfit', a Google Font you imported earlier.

2. **Body Styles**:
   - Sets the background color of the entire page to a light bluish shade (`hsl(212, 45%, 89%)`).

3. **Typography**:
   - **h1 Styles**: 
     - Sets the font size to `1.3rem`.
     - Color is a dark shade of blue (`hsl(218, 44%, 22%)`).
     - Adds a margin on top for spacing.
   - **p Styles**: 
     - Sets the font size to `0.938rem`.
     - Color is a muted blueish-gray (`hsl(220, 15%, 55%)`).

4. **Layout & Container Styles**:
   - **.main-container**: 
     - Spans the full viewport width (`100vw`) and 90% of the viewport height (`90vh`).
     - Centers its child elements both vertically (`align-items: center`) and horizontally (`justify-content: center`).
   - **.container**: 
     - Has a white background.
     - Centered with a width of 22% of its parent.
     - Rounded corners using `border-radius`.
     - Provides some padding for spacing inside the container.

5. **QR Code & Text Block Styles**:
   - **.qr-code-block & .qr-code**: 
     - Ensures the QR code image takes the full width and has rounded corners.
   - **.text-block**: 
     - Arranges text elements vertically with a spacing (`gap`) between them.
     - Text alignment is centered (`text-align: center`).

With these styles, you'll achieve a clean and responsive design for the QR code component. The specific colors and dimensions will result in a modern and appealing appearance on both desktop and mobile devices.
