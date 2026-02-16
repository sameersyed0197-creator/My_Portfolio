# Java Full Stack & AI/ML Developer Portfolio

A modern, responsive portfolio website showcasing Java Full Stack development and AI/ML projects.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Dark theme with smooth animations and transitions
- **Project Filtering**: Filter projects by category (Full Stack, AI/ML)
- **Smooth Scrolling**: Enhanced navigation experience
- **Interactive Elements**: Typing effect, skill bars, hover animations
- **Contact Form**: Get in touch section with form validation

## Sections

1. **Hero Section**: Introduction with name, title, and call-to-action buttons
2. **About**: Brief introduction and statistics
3. **Skills**: Technical skills organized by category:
   - Backend Development (Java, Spring Boot, Hibernate, Microservices)
   - Frontend Development (React, Angular, JavaScript, TypeScript)
   - AI/ML & Data Science (Python, TensorFlow, Scikit-learn, NLP)
   - Database & Tools (MySQL, MongoDB, Docker, Git)
4. **Projects**: Showcase of 6 projects (3 Full Stack + 3 AI/ML)
5. **Contact**: Contact form and social links

## Customization

### Update Personal Information

1. **index.html**:
   - Replace "Your Name" with your actual name
   - Update email, phone, and location in the contact section
   - Add your GitHub, LinkedIn, and Twitter links

### Add Your Projects

Replace the sample projects with your actual projects:

1. Add project images to the `assets/` folder (project1.jpg, project2.jpg, etc.)
2. Update project details in the HTML:
   - Project title
   - Description
   - Technologies used
   - GitHub and live demo links

### Adjust Skills

Modify skill percentages in the `style` attributes of `.skill-progress` divs to reflect your proficiency.

### Color Scheme

Edit CSS variables in `style.css`:
```css
:root {
    --primary-color: #00d4ff;
    --secondary-color: #6c63ff;
    --bg-dark: #0a0a0a;
    --bg-light: #1a1a1a;
}
```

## Project Images

Add your project screenshots to the `assets/` folder:
- project1.jpg - E-Commerce Platform
- project2.jpg - Sentiment Analysis
- project3.jpg - Task Management
- project4.jpg - Image Classification
- project5.jpg - Social Media Dashboard
- project6.jpg - Recommendation Engine

You can use placeholder images from:
- [Unsplash](https://unsplash.com/)
- [Pexels](https://www.pexels.com/)
- Create custom screenshots of your projects

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Font Awesome Icons

## How to Run

1. Open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   ```
3. Navigate to `http://localhost:8000`

## Deployment

Deploy your portfolio to:
- **GitHub Pages**: Free hosting for static sites
- **Netlify**: Drag and drop deployment
- **Vercel**: Fast and easy deployment
- **AWS S3**: Static website hosting

## License

Free to use and modify for your personal portfolio.
