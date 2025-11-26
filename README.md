# Personal Portfolio Website

A modern, responsive personal portfolio website showcasing skills, projects, and contact information. Built with HTML, CSS, and JavaScript.

## 🌟 Features

- **Modern Design**: Elegant blue and purple gradient theme with smooth animations
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Fade-in, slide-in, and reveal animations on scroll
- **Interactive Elements**: Hover effects, typing animation, and parallax effects
- **Contact Integration**: Direct links to email, phone, WhatsApp, and GitHub
- **Download CV**: One-click download functionality for CV/resume
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Accessibility**: Semantic HTML and ARIA labels for better accessibility

## 📁 Project Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styling and animations
├── script.js       # JavaScript functionality
├── profile.jfif    # Profile picture (add your own)
└── README.md       # This file
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (optional, for customization)

### Installation

1. **Clone or download** this repository to your local machine

2. **Add your profile picture**:
   - Save your profile picture as `profile.jfif` in the `portfolio` folder
   - The image should be a professional headshot (recommended size: 300x300px or larger)

3. **Open the website**:
   - Simply double-click `index.html` to open it in your default browser
   - Or right-click and select "Open with" your preferred browser

### Customization

#### Update Personal Information

Edit `index.html` to customize:

- **Name**: Line 47 - Update the name in the home section
- **Location**: Line 63 - Update your location
- **Email**: Line 281 - Update email address
- **Phone**: Line 288 - Update phone number
- **WhatsApp**: Line 295 - Update WhatsApp link
- **GitHub**: Line 302 - Update GitHub profile link

#### Update Content

- **About Section**: Lines 89-117 - Edit personal profile, education, and career objective
- **Skills**: Lines 127-211 - Modify technical and soft skills
- **Projects**: Lines 219-266 - Update project descriptions and technologies

#### Change Colors/Theme

Edit `styles.css` to customize the color scheme:

- **Primary Colors**: Lines 4-5 - Modify `--primary-blue` and `--primary-purple`
- **Gradients**: Lines 6-8 - Adjust gradient combinations
- **Background**: Line 6 - Change `--bg-light` for different background color

## 🎨 Sections

### 1. Home
- Hero section with animated gradient background
- Typing animation for professional title
- Call-to-action buttons
- Profile picture display

### 2. About Me
- Personal profile
- Education details
- Career objective

### 3. Skills
- Technical skills organized by category
- Soft skills
- Interactive skill tags with hover effects

### 4. Projects
- Project cards with descriptions
- Technology tags
- Hover animations

### 5. Contact
- Contact information cards
- Social media links
- Download CV button

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS variables, flexbox, grid, and animations
- **JavaScript (ES6+)**: Interactive functionality and animations
- **Google Fonts**: Poppins and Inter font families
- **Font Awesome**: Icons for social media and UI elements

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Features Breakdown

### Animations
- **Fade-in**: Elements fade in on page load
- **Slide-in**: Profile section slides in from the right
- **Reveal on Scroll**: Sections reveal as you scroll down
- **Typing Effect**: Dynamic typing animation for job titles
- **Parallax**: Gradient orbs move with scroll
- **Hover Effects**: Interactive hover states on cards and buttons

### Responsive Design
- Mobile-first approach
- Breakpoints at 968px and 600px
- Hamburger menu for mobile navigation
- Flexible grid layouts

### Interactive Elements
- Smooth scroll navigation
- Active section highlighting
- Download CV functionality
- Mobile menu toggle
- Notification system

## 📝 Customization Guide

### Adding a New Section

1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Add reveal animation class `reveal` to elements
4. Update navigation menu if needed

### Changing Profile Picture

1. Save your image as `profile.jfif` in the portfolio folder
2. Or update the filename in `index.html` line 69:
   ```html
   <img src="your-image-name.jpg" alt="Your Name" class="profile-image">
   ```

### Modifying Colors

Edit CSS variables in `styles.css` (lines 3-12):

```css
:root {
    --primary-blue: #4A90E2;    /* Change primary blue */
    --primary-purple: #9B59B6;  /* Change primary purple */
    /* ... other variables */
}
```

## 🔗 Links

- **Email**: dybrahimovic28@gmail.com
- **Phone**: +260 77 993 4886
- **WhatsApp**: [Contact via WhatsApp](https://wa.me/260779934886)
- **GitHub**: [Svotwazvikomborero28-sudo](https://github.com/Svotwazvikomborero28-sudo)

## 📄 License

This project is open source and available for personal use.

## 👤 Author

**Svotwa Zvikomborero**

- BSc ICT Student at Eden University
- Location: Lusaka, Zambia
- Email: dybrahimovic28@gmail.com

## 🙏 Acknowledgments

- Google Fonts for typography
- Font Awesome for icons
- Modern CSS techniques and animations

---

**Note**: Remember to update all placeholder content with your actual information before deploying or sharing your portfolio!

