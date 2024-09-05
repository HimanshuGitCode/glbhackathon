#Hackathon Sites

# GLBIM Hackathon 4.0 Website

This repository contains the source code for the official website of GLBIM Hackathon 4.0, an offline hackathon event scheduled for 23 November, 2024. The website serves as the main platform for participants, sponsors, and attendees to get information about the event, register, and view updates.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Key Features](#key-features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The GLBIM Hackathon 4.0 website is designed to provide detailed information about the hackathon, including the schedule, themes, prizes, and registration details. The website is mobile-responsive and incorporates modern web design practices to ensure an engaging user experience.

### Key Sections

- **Home:** The landing page with an event banner and links to register or join the event's WhatsApp group.
- **About:** Information about the organizing group and the GL Bajaj Institute of Management.
- **Event Details:** Overview of the hackathon, including venue, date, and a summary of the event.
- **Themes:** Details of the different themes participants can choose from, such as FinTech, EdTech, AR/VR, etc.
- **Glimpses:** A photo gallery showcasing moments from previous events.
- **Statistics:** Key metrics from past hackathons, including the number of registrations, attendees, and participating institutions.

## Technologies Used

- **HTML5:** Markup language used for structuring and presenting content on the web.
- **CSS3:** Used for styling the website, including layout, colors, and fonts.
- **Bootstrap 4:** A popular CSS framework for responsive, mobile-first front-end web development.
- **JavaScript:** For interactive elements, including event handling and dynamic content.
- **AOS (Animate On Scroll):** Library used for adding animations when scrolling through the website.
- **FontAwesome:** Icon toolkit used for adding scalable vector icons.
- **Swiper.js:** A modern mobile touch slider used for creating image carousels.
- **Google Fonts:** Custom fonts used for typography.

## Project Structure

index.html               # The main HTML file for the website
assets/
├── css/
│   ├── style-default-v5.min.css    # Default style for the website
│   ├── slider.css                  # Styles for the image slider
│   ├── prizes-v5.css               # Styles for the prizes section
│   ├── normalize-v5.min.css        # CSS reset for consistent styling across browsers
│   ├── font-v5.css                 # Custom fonts
│   ├── HemiHead-v5/style.css       # Specific font styling
├── img/
│   ├── banner/                     # Images for the banners
│   ├── glimpses/                   # Images for the Glimpses section
│   ├── themes/                     # Images for the Themes section
│   ├── favicon/                    # Favicon files
│   └── sponsors/                   # Sponsor logos and images
├── js/
│   ├── glimpses.js                 # JavaScript for the Glimpses section
│   └── vendor/
│       ├── modernizr-2.8.3.min.js  # Library for handling HTML5 and CSS3 features in older browsers


## Key Features

- **Responsive Design:** Ensures the website is accessible and looks good on all devices, including desktops, tablets, and smartphones.
- **Interactive Elements:** Includes animations, image carousels, and dynamic content to engage visitors.
- **Event Information:** Comprehensive details about the hackathon, its organizers, and event logistics.
- **Registration Links:** Direct access to registration through Devfolio and a link to join the official WhatsApp group.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/himanshugitcode/glbim-hackathon.git
   cd glbim-hackathon

