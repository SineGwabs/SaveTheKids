# Save the Kids Website
# Developer: Sinethemba Gwabeni

## Project Overview
This project is a website created for the NGO **Save the Kids** as part of a school assignment. The website aims to provide information about the organization's mission, goals, news, and ways to get involved, as well as allow users to stay updated with a newsletter signup. The website was built using HTML, CSS, and JavaScript, with additional elements such as a contact form and Google Form integration.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Functionality and Enhancements](#functionality-and-enhancements)
- [SEO Optimization](#seo-optimization)
- [JavaScript Validation](#javascript-validation)
- [Media Query Styling](#media-query-styling)
- [Future Improvements](#future-improvements)

## Features
- **Home Page**: Introduction to Save the Kids and a summary of the organization’s mission.
- **About Us Page**: Detailed information about the organization’s history, mission, and commitment to helping children.
- **Goals Page**: Outlines the primary objectives of the organization.
- **News Page**: Newsletter signup section integrated with a Google Form.
- **Contact Us Page**: Includes a customer contact form for inquiries and a map of the organization’s location.
- **Footer Date Stamp**: Displays the current date automatically using JavaScript.
- **Responsive Design**: Adapted for various screen sizes through media queries.

## Technologies Used
- **HTML**: For the structure of the website.
- **CSS**: For styling and layout, including media queries for responsive design.
- **JavaScript**: To enhance user interactivity, including form validation and footer date stamp.
- **Google Forms**: For newsletter subscription integration.
  
## Setup Instructions
1. Clone the repository to your local machine.
2. Open the project in a code editor (e.g., Visual Studio Code).
3. Open any HTML file in a browser to view the site.
4. Ensure the internet connection is active for the Google Form to load on the News page.

## Functionality and Enhancements
1. **JavaScript Date Stamp**: A JavaScript function was added to display the current date in the footer of each page, enhancing the site’s professionalism.
   - *Implementation*: A JavaScript function fetches the current date and dynamically updates the footer.
   
2. **Form Validation**: Basic JavaScript validation for the contact form was implemented to improve user experience.
   - Clears default text on click.
   - Checks for required fields like name and email, displaying an alert if left blank.

3. **Responsive Design**: Media queries were used to make the website responsive on smaller screens (below 960px).
   - *Changes*: Adjusted font sizes, padding, and layout styles to improve usability on mobile devices.

## SEO Optimization
To ensure the website is SEO-friendly, the following measures were implemented:
- **Meta Tags**: Added meta tags for description and keywords in each HTML file to improve search engine indexing.
- **Alt Text for Images**: Included descriptive `alt` attributes for all images to make content accessible and improve image SEO.
  
## JavaScript Validation
JavaScript validation was added to enhance the contact form:
1. **Clearing Fields**: Fields are cleared of initial text when clicked, preventing accidental submission of placeholder text.
2. **Required Fields Check**: Alerts the user if essential fields (like Name or Email) are left empty, ensuring complete submissions.

## Media Query Styling
A media query was added for screen widths below 960px to adjust the layout and make the site responsive.
- **Modifications Include**:
  - Adjusted layout spacing and font sizes.
  - Reorganized navigation for better usability on mobile devices.

## Future Improvements
- Add backend functionality to handle form submissions (currently using `mailto:`).
- Enhance form styling for better usability and appearance.
- Add more detailed validation to improve user experience.
- Consider adding an interactive map on the Contact Us page.

---
