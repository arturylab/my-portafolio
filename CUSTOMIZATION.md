# 🎯 Portfolio Customization Guide

This template provides a complete one-page portfolio website with dark theme, built using HTML and Tailwind CSS. Follow this guide to customize it with your personal information.

## 📋 Quick Setup Checklist

### 1. Personal Information
Replace the placeholder content in `index.html`:

- **Name**: Change "John Doe" to your name
- **Title**: Update "Full Stack Developer" to your professional title
- **Bio**: Replace the introduction paragraph with your own description
- **Contact Info**: Update email, LinkedIn, GitHub links
- **Location**: Change "San Francisco, CA" to your location

### 2. Skills Section
Update the skills grid with your technologies:
- Keep or modify existing skill cards
- Add new technologies using Font Awesome icons
- Remove skills you don't have
- Update skill names and icons as needed

### 3. Work Experience
Replace with your work history:
- Company names and positions
- Employment dates
- Key responsibilities and achievements
- Add or remove experience items as needed

### 4. Education
Update with your educational background:
- Institution names
- Degrees and programs
- Graduation dates
- Relevant achievements

### 5. Certificates & Courses
Add your certifications:
- Certificate names
- Issuing organizations
- Dates obtained
- Credential links (if available)

### 6. Projects
Showcase your projects:
- Project names and descriptions
- Technology stacks used
- GitHub repository links
- Live demo links
- Project images (optional)

### 7. Social Links
Update all social media and contact links:
- Email address
- LinkedIn profile
- GitHub profile
- Any additional social profiles

## 🎨 Customization Options

### Colors
The template uses Tailwind's gray color palette for the dark theme. To customize:
- Primary color: Currently blue (`bg-blue-600`, `text-blue-500`)
- Background: Gray shades (`bg-gray-900`, `bg-gray-800`)
- Text: Gray shades (`text-gray-100`, `text-gray-300`)

### Icons
All icons use Font Awesome. To change icons:
1. Visit [Font Awesome](https://fontawesome.com/icons)
2. Find your desired icon
3. Replace the icon classes (e.g., `fas fa-code`, `fab fa-python`)

### Profile Image
To add a real profile image:
1. Add your image to the `assets/` folder
2. Replace the icon placeholders with `<img>` tags
3. Use classes like `w-24 h-24 rounded-full object-cover`

### Sections
To add, remove, or reorder sections:
1. Update the navigation links in both desktop and mobile menus
2. Add/remove corresponding `<section>` elements
3. Update the JavaScript navigation highlighting

## 📱 Mobile Responsiveness

The template is fully responsive and includes:
- Mobile navigation menu
- Responsive grid layouts
- Appropriate text sizing
- Touch-friendly interface

## 🚀 Deployment

### Option 1: GitHub Pages
1. Create a new GitHub repository
2. Upload all files to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be available at `username.github.io/repository-name`

### Option 2: Netlify
1. Create account at [Netlify](https://netlify.com)
2. Drag and drop your project folder
3. Your site will be automatically deployed

### Option 3: Vercel
1. Create account at [Vercel](https://vercel.com)
2. Connect your GitHub repository
3. Automatic deployment on every commit

## 🔧 Development

### Local Development
Simply open `index.html` in your browser to view the site locally.

### Using a Local Server
For a better development experience:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

### Tailwind CSS Build Process (Optional)
If you want to customize Tailwind or use the CSS file:
1. Install Tailwind CSS
2. Configure `tailwind.config.js`
3. Build CSS using `npx tailwindcss build`

## 📝 Content Tips

### Writing Your Bio
- Keep it concise (3-4 sentences)
- Highlight your key skills and interests
- Show personality while maintaining professionalism
- Include what makes you unique

### Project Descriptions
- Focus on impact and results
- Mention technologies used
- Include challenges overcome
- Keep descriptions scannable

### Experience Bullets
- Start with action verbs
- Quantify achievements when possible
- Focus on relevant skills and technologies
- Keep each bullet concise

## 🎭 Accessibility

The template includes:
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images (add when you include images)
- Keyboard navigation support
- Good color contrast ratios

## 📊 SEO Optimization

To improve SEO:
1. Update the `<title>` tag with your name
2. Add meta description
3. Include relevant keywords naturally in content
4. Add Open Graph tags for social sharing
5. Ensure fast loading times

## 🔍 Testing

Before going live:
- [ ] Test on different devices and browsers
- [ ] Verify all links work correctly
- [ ] Check form functionality
- [ ] Validate HTML and CSS
- [ ] Test loading speed
- [ ] Ensure accessibility compliance

## 📞 Support

If you need help customizing this template:
1. Check the code comments for guidance
2. Refer to [Tailwind CSS documentation](https://tailwindcss.com/docs)
3. Look up Font Awesome icons at [fontawesome.com](https://fontawesome.com)

## 📄 License

This template is free to use and customize for personal and commercial projects.

---

**Happy coding! 🚀**
