![CI logo](/images/logo.jpg)

# Diva-Nails-Art-

## Purpose

The **Diva Nails Art** web application showcases luxury nail treatments. It provides users with a visually appealing and interactive platform to explore nail services, view examples of work, and easily get in touch with the business. The site features a modern design, responsive layout, and engaging multimedia elements.

## Value to Users

- **Visually Attractive**: Modern design with a dynamic video background.
- **Responsive**: Optimized for various devices including desktops, tablets, and mobiles.
- **User-Friendly Navigation**: Intuitive layout for easy access to information.
- **Engaging Media**: Includes a high-quality video background to capture user interest.
- **Direct Communication**: The contact section allows users to quickly get in touch with the salon for inquiries or appointments.
- **Visual Appeal**: High-quality images and a professional design enhance the user experience and reflect the luxury nature of the services offered.

## Deployment Procedure

- **To deploy the Diva Nails Art website, follow these steps**:

1 **Clone the Repository**:

Use git clone to clone the repository to your local machine:
git clone https://github.com/Diva81/Diva-Nails-Art-.git

2 **Navigate to the Project Directory**:

Move into the project's root directory:
cd diva-nails-art

3 **Set Up the Web Server**:

You can use a simple web server for deployment, such as Apache, Nginx, or even a Python HTTP server for development purposes:
python3 -m http.server

Or, if you're using Node.js:
npm install -g serve
serve -s .

4 **Deployment**:

Deploy the Site:

. Use a hosting service like GitHub Pages, Netlify, or Vercel for deployment.
Follow the specific instructions for your chosen platform to deploy the site.
Update the Live Link:

. After deploying, update this README.md file with the URL of your live site.
Live Site
You can view the live site here: Diva Nails Art

## Screenshots

Home Page
Services Section
Contact Section

## Code Attribution

- **CSS Libraries**

**Bootstrap 4.5.2**: Used for responsive layout and components. Bootstrap Documentation
<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">

- **JS Libraries**

**jQuery 3.5.1**: Required by Bootstrap's JavaScript plugins. jQuery Documentation
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>

**Popper.js 2.9.3**: Required by Bootstrap for tooltips and popovers. Popper.js Documentation
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>

**Bootstrap 4.5.2**: JavaScript components for interactive elements like modals and dropdowns.
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

## Code Organization

**File Structure**

diva-nails-art/
│
├── assets/
│   ├── images/
│   ├── screenshots/
│   └── video/
│
├── css/
│   └── styles.css
│
├── index.html
└── README.md

**HTML**: 
The HTML structure is defined in index.html, with clear, descriptive comments marking each section (e.g., navigation, hero section, services, contact).

**CSS**: 
All custom styling is placed in styles.css, which is linked in the <head> of the HTML document. The CSS is organized into well-defined sections with comments for readability.

**Assets**: 
Images, screenshots, and videos are stored in the assets/ directory, organized into subdirectories for easier management.

## Code Readability

**Consistent Indentation**: The code follows consistent 4-space indentation for clarity.
**Commenting**: Each section in the HTML and CSS is clearly commented, explaining its purpose and any significant code decisions.
**File Naming**: All files are named using lowercase letters and hyphens, ensuring compatibility across different platforms.

## Development Log
August 20, 2024: Implemented responsive navigation bar and centered logo.
August 21, 2024: Added video background to the hero section and adjusted text alignment.
August 22, 2024: Fixed footer alignment and updated CSS styles for improved readability.
August 23, 2024: Finalized README.md with detailed deployment instructions and updated live site link.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contributing

If you would like to contribute to this project, please follow these guidelines:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## Contact

For questions or feedback, please contact [Diva Nunes](divanunes81@gmail.com).
