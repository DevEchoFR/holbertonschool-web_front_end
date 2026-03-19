# CSS Advanced - Techium

This project is part of the Holberton School front-end curriculum.
The goal is to style the Techium website using advanced CSS techniques, creating a visually stunning and responsive digital agency website.

## 🎯 Learning Objectives

By the end of this project, you should be able to:

- Use CSS selectors with precision and understand specificity
- Apply advanced layout techniques (Flexbox, CSS Grid)
- Create responsive designs with media queries
- Implement CSS animations and transitions
- Build a cohesive design system
- Use CSS preprocessors effectively
- Optimize CSS for performance
- Create accessible and maintainable stylesheets
- Apply modern CSS best practices

## 📋 Requirements

- Allowed editors: `vi`, `vim`, `emacs`, VS Code
- All files must end with a new line
- No external CSS frameworks (Bootstrap, Tailwind, etc.)
- CSS must be well-organized and properly commented
- Mobile-first responsive design approach
- Cross-browser compatibility
- Valid CSS3 code

## 📁 Project Structure

```
CSS_advanced/
├── styles/
│   ├── 1-style.css through 32-style.css    (Progressive CSS tasks)
│   └── README.md                           (Styles documentation)
│
├── images/
│   └── [Image assets used in styling]      (Portfolio images)
│
└── README.md (this file)
```

## 🎨 Key CSS Concepts Covered

### **1. Selectors & Styling Fundamentals**
- Element, class, and ID selectors
- Pseudo-classes (`:hover`, `:focus`, `:active`)
- Pseudo-elements (`::before`, `::after`)
- Attribute selectors
- CSS specificity and cascade

### **2. Typography & Text Styling**
- Font selection and web fonts
- Text properties (size, weight, spacing, alignment)
- Line height and letter spacing
- Text shadows and effects
- Font fallbacks and @font-face

### **3. Box Model & Spacing**
- Margins, padding, and borders
- Box-sizing property
- Negative margins
- Collapsing margins
- Spacing conventions

### **4. Colors & Backgrounds**
- Color systems (hex, RGB, HSL)
- Background images and gradients
- Opacity and transparency
- Color overlays
- Background properties

### **5. Layout Techniques**
- Flexbox layout
- CSS Grid
- Positioning (static, relative, absolute, fixed)
- Float and clear
- Display properties
- Responsive grid systems

### **6. Responsive Design**
- Mobile-first approach
- Media queries and breakpoints
- Flexible typography
- Responsive images
- Fluid layouts
- Container queries

### **7. Advanced Effects**
- Transitions and animations
- Transform properties
- Keyframes
- Timing functions
- 3D transforms
- Filter effects

### **8. State & Interaction**
- Hover effects
- Focus states for accessibility
- Active states
- Disabled states
- Loading animations

### **9. Accessibility in CSS**
- Color contrast requirements
- Focus indicators
- Reduced motion preferences
- Semantic color usage
- ARIA-friendly styling

### **10. Performance Optimization**
- Critical CSS
- CSS minification
- Reducing redundancy
- Efficient selectors
- Media query optimization
- Avoiding reflows and repaints

## 📚 How to Use This Project

### **1. Progressive Learning**
- Start with style files numbered from lowest to highest
- Each file builds upon previous concepts
- Complete the HTML structure first (from `html_advanced`)
- Apply CSS styles to corresponding HTML files

### **2. File Association**
```
1-style.css     → Basic styling fundamentals
5-style.css     → Layout and positioning
10-style.css    → Advanced selectors and properties
15-style.css    → Responsive design
20-style.css    → Flexbox layouts
25-style.css    → Grid systems
30-style.css    → Animations and effects
```

### **3. Development Workflow**
```bash
# 1. Navigate to the project
cd CSS_advanced

# 2. Link CSS file to HTML file
<!-- In your HTML file -->
<link rel="stylesheet" href="styles/X-style.css">

# 3. Open in browser
xdg-open ../html_advanced/index.html

# 4. Make changes and check browser
# (Use Live Server for automatic refresh)
```

## 🎯 Design System

The Techium website uses a consistent design system:

### **Color Palette**
- Primary colors: Corporate blues, grays
- Accent colors: Professional highlights
- Neutral colors: Text and backgrounds
- Semantic colors: Success, warning, error states

### **Typography**
- Heading hierarchy (H1-H6)
- Body text font
- Monospace for code
- Consistent line heights
- Readable font sizes

### **Spacing Scale**
- Consistent margin/padding units
- Vertical rhythm
- Proportional spacing
- Breathing room around elements

### **Component Styles**
- Buttons (primary, secondary, disabled)
- Cards and containers
- Navigation elements
- Form elements
- Social icons

## 🔍 CSS Best Practices Applied

✅ **Modular CSS**
- Organize by component
- Keep styles scoped
- Avoid style conflicts

✅ **DRY Principle**
- Reuse common styles
- Use CSS variables where applicable
- Avoid repetition

✅ **Naming Conventions**
- Semantic class names
- BEM or similar methodology
- Clear, descriptive names

✅ **Performance**
- Minimal selectors
- Avoid !important
- Optimize media queries
- Efficient animations

✅ **Maintainability**
- Clear comments
- Logical organization
- Easy to locate styles
- Simple to update

## ✅ Validation & Testing

### CSS Validation
Validate your CSS with:
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- Browser DevTools

### Testing Checklist
- ✅ View on desktop (1920px, 1366px, 1024px)
- ✅ View on tablet (768px, 1024px)
- ✅ View on mobile (375px, 768px)
- ✅ Test touch interactions
- ✅ Check color contrast (WCAG AA standard)
- ✅ Verify on multiple browsers
- ✅ Test keyboard navigation
- ✅ Validate with CSS validator

### Browser Compatibility
Target support for:
- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)

## 📐 Responsive Breakpoints

```css
/* Mobile First Approach */
/* 375px - 767px */    Mobile phones
/* 768px - 1023px */   Tablets
/* 1024px - 1366px */  Small desktop
/* 1367px+ */          Large desktop
```

## 🚀 Getting Started

### Step 1: Set Up
```bash
cd CSS_advanced
```

### Step 2: View the Website
```bash
# Open HTML file in browser
xdg-open ../html_advanced/index.html
```

### Step 3: Apply Styles
```html
<!-- Link CSS in your HTML head -->
<link rel="stylesheet" href="styles/1-style.css">
```

### Step 4: Develop
- Edit CSS files
- Test in browser
- Verify responsiveness
- Check browser DevTools

### Step 5: Validate
```bash
# Validate CSS
# Open https://jigsaw.w3.org/css-validator/
```

## 📊 File Statistics

- **Total CSS Files:** 32 progressive style sheets
- **Coverage:** Complete website styling
- **Breakpoints:** Mobile-first responsive design
- **Components:** Headers, navigation, cards, forms, buttons

## 🎓 Learning Path

**Beginner:**
- Files 1-10: CSS fundamentals
- Focus: Selectors, properties, box model

**Intermediate:**
- Files 11-20: Layouts and responsive design
- Focus: Flexbox, media queries, positioning

**Advanced:**
- Files 21-32: Effects and optimization
- Focus: Animations, transitions, performance

## ⚙️ Tools & Technologies

- **CSS3** - Modern CSS features
- **Preprocessors** - Optional (SASS/SCSS)
- **Developer Tools** - Browser DevTools
- **Validators** - W3C CSS Validator
- **Testing** - Manual cross-browser testing

## 🔗 Resources

- [MDN CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS Tricks](https://css-tricks.com/)
- [Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Web.dev CSS Learning](https://web.dev/learn/css/)
- [W3C CSS Specifications](https://www.w3.org/Style/CSS/)

## 📝 File Compliance

All CSS files meet the following requirements:
- End with a newline character
- Valid CSS3 syntax
- Well-organized and commented
- Semantic naming conventions
- Mobile-first responsive design
- Cross-browser compatible

## 🎯 Expected Outcomes

After completing this project, you will have:
- ✅ Created a fully styled, responsive website
- ✅ Mastered advanced CSS techniques
- ✅ Built a reusable design system
- ✅ Learned responsive design principles
- ✅ Understood CSS performance optimization
- ✅ Practiced accessibility in CSS
- ✅ Created professional-quality stylesheets

## 📖 Related Projects

- **HTML Advanced** - The HTML structure this CSS styles
- **Full Techium Website** - Combined HTML + CSS project

## 👨‍💼 Author

Holberton School Student

## 📄 License

This project is part of the Holberton School curriculum.

---

**Last Updated:** March 2026  
**Status:** ✅ Ready for learning and development