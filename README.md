Description

This project is a responsive webpage designed to showcase a portfolio. The webpage includes a fixed navbar, a collapsible left menu, a main content area, a right-side panel, and a footer. It is fully responsive and adjusts its layout based on the screen size.

Features

Fixed Navbar: Stays at the top of the page when scrolling.

Collapsible Left Menu: Users can toggle the visibility of the left menu.

Main Content Area: Displays information about the portfolio.

Right-Side Panel: Shows contact information.

Footer: Includes copyright information.

Responsive Design: Adjusts layout and scale for various screen sizes.

File Structure

responsive_webpage/
├── index.html    # Main HTML file

How to Run the Project

Prerequisites

A web browser (e.g., Chrome, Firefox, Edge).

Visual Studio Code (optional, for editing the code).

Steps

Clone or download the project to your local machine.

Open the project folder in Visual Studio Code or any text editor.

Open the index.html file in a web browser:

In Visual Studio Code, right-click on the index.html file and select Open with Live Server (requires the Live Server extension).

Alternatively, double-click the index.html file to open it in your default browser.

Testing Responsive Features

Resize the browser window to observe how the layout adjusts.

Use the menu toggle button in the navbar to collapse or expand the left menu.

Responsive Behavior

Screen Width

Scaling Behavior

<= 600px

Shrinks to 50%

601px to 700px

Shrinks to 75%

701px to 767px

Shrinks to 80%

768px to 1600px

Shrinks to 90%

> 1600px

Full size (100%)

Customization

To update the portfolio sections:

Modify the index.html file:

Update the content inside <section id="about">, <section id="skills">, and <section id="projects">.

Edit contact details in the right panel.

License

This project is open source and available under the MIT License.