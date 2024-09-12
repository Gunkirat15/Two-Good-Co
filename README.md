Interactive Web Page with GSAP and Locomotive Scroll

This project is a dynamic and responsive web page that integrates GSAP (GreenSock Animation Platform) and Locomotive Scroll to create fluid animations, custom cursor effects, and smooth scrolling interactions. The page features custom animations for the navbar, videos, and various page elements to enhance user experience.

Smooth Scrolling: Powered by Locomotive Scroll for enhanced scroll interactions.
Custom Cursor: Unique mouse cursor animation that scales and moves dynamically across the page.
Video Interactivity: Video plays and pauses on click and reveals a play button on hover.
Loading Animations: Elements on the page load with stylish animations using GSAP.
Responsive Design: Fully responsive layout for both desktop and mobile screens.
Hover Effects: Interactive hover animations on various elements.
Technologies Used

HTML5: Markup structure of the page.
CSS3: Styling for layout and responsiveness.
GSAP: Animation library for creating smooth, timeline-based animations.
Locomotive Scroll: Smooth scrolling effect and scroll-triggered animations.
JavaScript (ES6): DOM manipulation and event handling.
Setup and Installation

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
Navigate to the project directory:
bash
Copy code
cd your-repo-name
Install dependencies: This project relies on GSAP and Locomotive Scroll. Include these libraries via CDN or download them locally:
GSAP:
html
Copy code
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.7.1/gsap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.7.1/ScrollTrigger.min.js"></script>
Locomotive Scroll:
html
Copy code
<script src="https://unpkg.com/locomotive-scroll@4.1.3/dist/locomotive-scroll.min.js"></script>
Open the project: Open the index.html file in your browser to view the page.
File Structure

bash
Copy code
├── index.html             # Main HTML structure
├── styles.css             # Main stylesheet for styling the page
├── script.js              # JavaScript for animations and interactions
├── assets/                # Folder for storing images and other media
└── README.md              # Project documentation (this file)
Usage

Navbar Animation: The navbar slides out of view when the page scrolls past a certain point and comes back on scroll up.
Video Container: Hover over the video container to reveal a play button, and click the video to toggle between play and pause.
Custom Cursor: The mouse cursor scales up when hovering over certain elements (with the class .child).
Scroll Animations: As you scroll through the page, images, text, and other elements are animated using GSAP and Locomotive Scroll.
Responsive Behavior
The project is optimized for both desktop and mobile devices. CSS media queries ensure that the layout adapts to different screen sizes.

License

This project is licensed under the MIT License. You are free to use, modify, and distribute this project for personal and commercial purposes.