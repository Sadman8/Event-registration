# Event-registration

This repository contains the codebase for the Industry-Academia Collaboration Summit 2025 (IACS-2025) event website. The summit aims to foster stronger ties between academic institutions and industry leaders, addressing the critical gaps between education and employability.

## Features and Functionality

*   **Event Information:** Displays key details about the IACS-2025 event, including the theme, date, time, and venue.
*   **About Section:** Provides a detailed description of the event's purpose and objectives.
*   **Speakers Section:** Showcases the trainers and speakers participating in the summit, including their names, positions, and social media links.
*   **Schedule Section:** Presents the event schedule, including session titles, timings, venues, and descriptions.
*   **Venue Information:**  Provides details on the event location, including a Google Maps integration.
*   **Partners Section:** Highlights the organizations supporting the event, including strategic partners, recruiting partners, and club partners.
*   **Contact Information:** Offers contact details for inquiries and support.
*   **Registration:** A prominent "Register Now" button links to the event registration page.
*   **Countdown Timer:**  Displays a countdown timer to the event date.
*   **Responsive Design:** The website is designed to be responsive and accessible across various devices.
*   **Social Media Integration:** Meta Pixel Code and Google Tag for tracking.
*   **Popup Message:** Displays a popup message with information, controlled by Javascript.

## Technology Stack

*   **HTML:**  The core structure and content of the website.
*   **CSS:** Styling and visual presentation, including Bootstrap for layout and custom styles in `css/style.css`.
*   **JavaScript:**  Interactive elements and dynamic functionality, including:
    *   `js/app.js`: Main application logic, including smooth scrolling, header effects, and mobile navigation.
    *   `js/contactform.js`:  Contact form submission handling (though it appears to rely on a server-side script `contactform/contactform.php` that is not included in the repository).
    *   `lib/jquery/jquery.min.js`: jQuery library for DOM manipulation and AJAX.
    *   `lib/bootstrap/js/bootstrap.bundle.min.js`: Bootstrap JavaScript components.
    *   `lib/easing/easing.min.js`:  Easing functions for animations.
    *   `lib/superfish/hoverIntent.js`:  hoverIntent plugin.
    *   `lib/superfish/superfish.min.js`: Superfish menu plugin.
    *   `lib/wow/wow.min.js`:  WOW.js animation library.
    *   `lib/venobox/venobox.min.js`: Venobox lightbox plugin.
    *   `lib/owlcarousel/owl.carousel.min.js`:  Owl Carousel library.
*   **Bootstrap:** CSS framework for responsive layout and styling (v4).
*   **Font Awesome:** Icon library.
*   **Google Fonts:** Used for specific fonts.
*   **Venobox:** Lightbox plugin used for the video.

## Prerequisites

To run this website locally, you will need:

*   A web browser (e.g., Chrome, Firefox, Safari).
*   A web server (e.g., Apache, Nginx, or a simple Python HTTP server) if you want to test the contact form submission or any other server-side functionality.
*   A basic understanding of HTML, CSS, and JavaScript.

## Installation Instructions

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Sadman8/Event-registration.git
    cd Event-registration
    ```

2.  **Open `index.html` in your web browser:** You can directly open the `index.html` file in your browser to view the website.

3.  **(Optional) Set up a local web server:**

    *   **Using Python:**  Navigate to the project directory in your terminal and run:

        ```bash
        python -m http.server 8000
        ```

        Then, access the website at `http://localhost:8000`.

## Usage Guide

1.  **Navigate the website:** Use the navigation menu at the top of the page to explore different sections of the website.
2.  **View speaker profiles:** Click on a speaker's image or name to view their detailed information.
3.  **Explore the event schedule:**  Review the schedule to find sessions of interest.
4.  **Register for the event:** Click on the "Register Now" button to access the registration page.
5. **Popup Message:** Ensure javascript is enabled in the browser to see the popup message. The popup displays only once per 24 hours, controlled by `localStorage`.

## API Documentation

There are no APIs included in the downloaded files, and the project appears to be a static front-end website.  The `js/contactform.js` file attempts to submit a form to `contactform/contactform.php`, but this PHP file is not included in the repository. To make it work you need to create and deploy a `contactform.php` to handle form submissions.

## Contributing Guidelines

Contributions to this project are welcome. To contribute:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive commit messages.
4.  Push your changes to your forked repository.
5.  Submit a pull request to the main repository.

## License Information

No license information is provided in the repository. All rights are reserved unless otherwise specified.

## Contact/Support Information

For any questions or support requests, please contact:

Career Development Center (CDC)
Daffodil International University
Email: cdc@daffodilvarsity.edu.bd
Phone: +8801847-334705