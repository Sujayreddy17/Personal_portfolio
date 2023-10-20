You've provided an HTML file that complements the CSS code you shared earlier. This HTML file represents the structure of a personal portfolio website. Here's a breakdown of the HTML elements and their functionality:

Meta tags in the <head> section:

Define the character set and the viewport for responsive design.
Set the page title to "Personal-Portfolio."
Link to your external stylesheet (style.css).
Include the Font Awesome kit for icons.
<body> element:

The main content of your website is enclosed within this element.
Header section:

Contains a navigation bar with a logo and links to different sections of the website.
A button with the "fa-bars" icon is used to open the side menu, and a button with the "fa-xmark" icon is used to close it.
About section:

Contains information about yourself, including a photo, a short bio, and tabs for displaying skills, experience, and education.
Services section:

Presents a list of services with icons, descriptions, and "Learn more" buttons.
Portfolio section:

Displays your work in a grid format with images and overlay information.
Provides download links for detailed project descriptions.
Contact section:

Contains your contact information, social media links, a download link for your CV, and a contact form.
The form collects the user's name, email, and message and submits it to a Google Sheets script for processing.
A message element with the id "msg" is used to display success or error messages.
JavaScript scripts:

The first script handles tab switching for the "About" section.
The second script manages the opening and closing of the side menu.
The third script sends form data to a Google Sheets script when the user submits the contact form.
This HTML structure, in combination with your CSS, creates a complete personal portfolio website. You may want to ensure that the file paths for images and resources are correct and that your server or hosting environment can handle the Google Sheets API request. Additionally, make sure your Google Sheets script is correctly configured to receive and process the form data.
