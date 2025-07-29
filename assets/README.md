# Sample images and assets for portfolio

This folder should contain:

## Profile Images
- `profile.jpg` or `profile.png` - Your profile photo (recommended size: 400x400px)
- `profile-small.jpg` - Smaller version for sidebar (200x200px)

## Project Images
- `project1.jpg` - E-commerce platform screenshot
- `project2.jpg` - Task management app screenshot
- `project3.jpg` - Data analytics dashboard screenshot
- Add more project images as needed

## Documents
- `resume.pdf` - Your resume/CV for download
- `portfolio.pdf` - Portfolio presentation (optional)

## Icons/Logos
- `favicon.ico` - Website favicon
- `logo.png` - Personal logo (optional)

## Image Optimization Tips
- Use WebP format for better compression
- Optimize images for web (compress without losing quality)
- Use appropriate alt text for accessibility
- Recommended tools:
  - TinyPNG for compression
  - Squoosh for format conversion
  - Canva for creating graphics

## Adding Images to HTML
Replace the icon placeholders with your images:

```html
<!-- Replace this -->
<div class="w-24 h-24 mx-auto mb-4 bg-gray-700 rounded-full flex items-center justify-center">
    <i class="fas fa-user text-3xl text-gray-300"></i>
</div>

<!-- With this -->
<img src="assets/profile.jpg" alt="Your Name" class="w-24 h-24 mx-auto mb-4 rounded-full object-cover">
```

For project images:
```html
<!-- Replace the gradient background -->
<div class="h-48 bg-gradient-to-br from-blue-600 to-blue-800 flex items-center justify-center">
    <i class="fas fa-shopping-cart text-white text-4xl"></i>
</div>

<!-- With this -->
<img src="assets/project1.jpg" alt="Project Name" class="h-48 w-full object-cover">
```
