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



# Responsive Design Documentation for QR Code Component

## Introduction

This documentation outlines the design and development approach taken to create a responsive QR Code component web page. The primary objective is to ensure optimal user experience across various devices and screen sizes. The responsive design utilizes CSS media queries to adapt the layout and styling based on the viewport width.

## Table of Contents

1. [Universal Styles](#universal-styles)
2. [Typography](#typography)
3. [Layout and Container Styles](#layout-and-container-styles)
4. [Responsive Adjustments](#responsive-adjustments)
5. [Conclusion](#conclusion)

## Universal Styles

- **Reset Styles**: 
  - Resets default margins, paddings, and box-sizing for consistent rendering across browsers.
  - Sets the default font to 'Outfit', a Google Font, to maintain consistent typography.

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Outfit', sans-serif;
}
```

## Typography

- **Heading and Paragraph Styles**: 
  - Defines font sizes, colors, and spacing for the primary headings and paragraphs on the page.

```css
h1 {
  font-size: 1.3rem;
  color: hsl(218, 44%, 22%);
  margin-top: 1em;
}

p {
  font-size: 0.938rem;
  color: hsl(220, 15%, 55%);
}
```

## Layout and Container Styles

- **Main Container**: 
  - Centers content vertically and horizontally within the viewport.

```css
.main-container {
  width: 100vw;
  height: 90vh;
  display: flex;
  align-items: center;
  justify-content: center;
}
```

- **Container**: 
  - Provides styling for the primary content container, including background color, border-radius, and padding.

```css
.container {
  background-color: hsl(0, 0%, 100%);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 90%;
  max-width: 400px;
  margin: auto;
  border-radius: 20px;
  padding: 1em;
}
```

## Responsive Adjustments

- **Media Queries**: 
  - Utilizes CSS media queries to adjust layout and styling for various screen sizes.
  
```css
@media (min-width: 768px) {
  .container {
    width: 70%;
  }
}

@media (min-width: 1024px) {
  .container {
    width: 50%;
  }
}
```

- **Adjustments**: 
  - The container width adjusts dynamically based on the viewport width, ensuring a responsive design.

## Conclusion

This documentation provides a comprehensive overview of the design and development strategy employed to create a responsive QR Code component. By utilizing CSS media queries and thoughtful styling, the web page ensures optimal viewing and user experience across desktops, tablets, and mobile devices. Continuous testing and refinement are recommended to maintain consistency and performance across various platforms.
