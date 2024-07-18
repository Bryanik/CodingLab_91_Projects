# Profile Card UI Design

## Introduction

This project demonstrates a profile card UI design using HTML and CSS. The card includes a profile image, name, job title, social media links, action buttons, and analytics data. The design is responsive and features hover animations for interactive elements.

## Features

- **Profile Image**: Displays a circular profile picture.
- **Name and Job Title**: Shows the name and job title of the individual.
- **Social Media Links**: Provides links to social media profiles with corresponding icons.
- **Action Buttons**: Includes buttons for subscribing and messaging.
- **Analytics Data**: Displays likes, comments, and shares statistics.
- **Hover Animations**: Adds interactive hover effects to elements.

## Technologies Used

- **HTML**: The structure of the profile card.
- **CSS**: Styling and layout of the profile card.
- **Google Fonts (Poppins)**: Font styling for text.
- **Boxicons**: Icons for social media links and analytics data.

## How to Use

1. **Clone or Download**: Clone this repository or download the ZIP file.
2. **Open in Browser**: Open `index.html` in your browser to view the profile card.
3. **Customization**: Customize the profile information, links, and styles as needed.

## Code Overview

### HTML

The HTML file provides the structure for the profile card.

### CSS

The CSS file includes styles for the profile card, layout, and hover animations:

### JavaScript

The JavaScript function is used to send an email when the "Message" button is clicked:

```javascript
function sendMail() {
  window.location.href = "mailto:bikechukwu2@gmail.com";
}
```

## How to Customize

- **Profile Image**: Replace the image source (`src`) in the `img` tag with your own image.
- **Name and Job Title**: Update the text in the `.name` and `.job` spans.
- **Social Media Links**: Change the `href` attributes in the social media links and update the `i` tags for different icons.
- **Action Buttons**: Modify the button text and actions as needed.
