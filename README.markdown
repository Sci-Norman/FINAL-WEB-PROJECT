# Modern Portfolio Website >LINK TO WEBSITE: https://norman1website.vercel.app/

A responsive, multipage portfolio website built to showcase web development skills using HTML5, CSS3, and JavaScript. The website features a clean, modern design with interactive elements, including an image slider and form validation, and is optimized for both desktop and mobile devices.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Setup and Installation](#setup-and-installation)
- [Deployment](#deployment)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project fulfills the requirements of designing, coding, and deploying a multipage website. It includes three main pages—Home, About, and Contact—demonstrating proficiency in semantic HTML5, advanced CSS3 styling, and interactive JavaScript functionality. The website is fully responsive, ensuring a seamless user experience across various screen sizes.

## Features
- **Multipage Structure**: Includes Home, About, and Contact pages with consistent navigation.
- **Responsive Design**: Adapts to different screen sizes using CSS media queries.
- **Interactive Elements**:
  - Image slider on the Home page with automatic and manual navigation.
  - Form validation on the Contact page to ensure valid user input.
- **Modern Aesthetics**: Utilizes gradients, shadows, and smooth transitions for a professional look.
- **Modular Code**: Separates HTML, CSS, and JavaScript into independent files for maintainability.

## Technologies Used
- **HTML5**: Semantic structure for accessibility and SEO.
- **CSS3**: Flexbox, gradients, media queries, and transitions for styling and responsiveness.
- **JavaScript**: Dynamic functionality for the image slider and form validation.
- **External Resources**: Placeholder images from [Picsum Photos](https://picsum.photos/).

## File Structure
```
modern-portfolio/
├── index.html              # Home page
├── about.html              # About page
├── contact.html            # Contact page
├── styles.css              # Shared CSS styles (navigation, general layout)
├── home.css                # Home page-specific CSS (hero, slider)
├── about.css               # About page-specific CSS
├── contact.css             # Contact page-specific CSS (form)
├── slider.js               # Image slider functionality
├── form-validation.js      # Contact form validation
└── README.md               # Project documentation
```

## Setup and Installation
1. **Clone or Download**:
   - Clone the repository: `git clone <repository-url>` or download the project files.
2. **Navigate to Project Directory**:
   - `cd modern-portfolio`
3. **Open Locally**:
   - Open `index.html` in a web browser to view the website locally.
   - Alternatively, use a local server (e.g., `npx http-server` or VS Code's Live Server extension) for a better development experience.

No additional dependencies or build tools are required, as the project uses vanilla HTML, CSS, and JavaScript.

## Deployment
To deploy the website to a live server:
1. **Choose a Hosting Platform**:
   - Recommended platforms: [GitHub Pages](https://pages.github.com/), [Netlify](https://www.netlify.com/), or [Vercel](https://vercel.com/).
2. **Steps for Deployment**:
   - **GitHub Pages**:
     - Push the project to a GitHub repository.
     - Enable GitHub Pages in the repository settings, selecting the `main` branch and `/ (root)` folder.
   - **Netlify**:
     - Drag and drop the project folder into Netlify's web interface or link the GitHub repository for automatic deployment.
   - **Vercel**:
     - Import the repository via Vercel's dashboard and deploy with default settings.
3. **Custom Images**:
   - Replace placeholder images in `index.html` (e.g., `https://picsum.photos/1000/400?image=1`) with your own images, hosted locally or on a CDN.

## Usage
- **Navigation**: Use the fixed navigation bar to switch between Home, About, and Contact pages.
- **Home Page**:
  - View the hero section and interact with the image slider using "Prev" and "Next" buttons or wait for automatic transitions.
- **About Page**:
  - Read information about the developer and their skills.
- **Contact Page**:
  - Fill out the contact form, which includes client-side validation for name (minimum 2 characters), email (valid format), and message (minimum 10 characters).
  - Successful submissions display an alert and reset the form.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Make changes and commit: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request with a clear description of your changes.

Please ensure code follows the project's style conventions and includes appropriate comments.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
*Built with ❤️ by [Your Name]*
