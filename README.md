# 📊 Bento Grid

A responsive **Bento Grid** layout built as part of the **TechCrush Frontend Development Bootcamp**.

The project focuses on recreating a modern dashboard-style layout from a provided design while practicing **CSS Grid, responsive design, typography, spacing, and component-based styling**.

## 🖥️ Preview

### Desktop

![Desktop Preview](design/desktop-design.jpg)

### Mobile

![Mobile Preview](design/mobile-design.jpg)

## 🛠️ Built With

* HTML5
* CSS3
* CSS Grid
* Flexbox
* CSS Custom Properties
* CSS Media Queries
* Responsive Web Design
* DMSans Font

## ✨ Features

* Responsive Bento-style grid layout
* Desktop and mobile layouts
* CSS Grid for complex card positioning
* Flexible card sizing and spacing
* Custom typography using the provided DMSans fonts
* Reusable CSS classes
* Responsive illustrations and content
* Design colors implemented using CSS custom properties

## 📂 Project Structure

```text
Assignment/
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── fonts/
│   │   ├── DMSans-Italic-VariableFont_opsz,wght.ttf
│   │   ├── DMSans-VariableFont_opsz,wght.ttf
│   │   ├── static/
│   │   │   ├── DMSans-Medium.ttf
│   │   │   ├── DMSans-MediumItalic.ttf
│   │   │   └── DMSans-Regular.ttf
│   │   ├── OFL.txt
│   │   └── README.txt
│   └── images/
│       ├── favicon-32x32.png
│       ├── illustration-ai-content.webp
│       ├── illustration-audience-growth.webp
│       ├── illustration-consistent-schedule.webp
│       ├── illustration-create-post.webp
│       ├── illustration-five-stars.webp
│       ├── illustration-grow-followers.webp
│       ├── illustration-multiple-platforms.webp
│       └── illustration-schedule-posts.webp
├── design/
│   ├── desktop-design.jpg
│   └── mobile-design.jpg
├── index.html
└── style-guide.md
```

## 🧠 What I Learned

### CSS Grid

This assignment gave me more practical experience using CSS Grid to create a complex multi-card layout.

Instead of treating each card independently, the grid allows the overall page structure to control how the cards occupy available space.

This helped reinforce an important CSS principle:

> **The parent should usually be responsible for the layout of its children.**

### Responsive Design

The layout has different requirements at desktop and mobile sizes, so media queries are used to restructure the grid for smaller screens.

The goal was not simply to shrink the desktop design, but to allow the cards to reorganize into a more appropriate layout for smaller screens.

### CSS Custom Properties

The design colors were defined using CSS variables, making the stylesheet easier to maintain and keeping the implementation consistent with the provided style guide.

### Typography

The provided **DMSans** font was incorporated into the project to more closely match the reference design.

Working with the supplied font files also provided experience with using local font assets rather than relying entirely on system fonts.

### Component-Based Thinking

Although the project uses plain HTML and CSS, the cards were treated as reusable visual components.

Common styling can therefore be shared across similar elements instead of repeatedly writing the same CSS rules.

## 📱 Responsive Design

The design references were provided at:

* **Desktop:** 1440px
* **Mobile:** 375px

The implementation uses CSS media queries to adapt the grid and content for smaller screens.

The layout was also intended to remain usable across intermediate viewport sizes rather than being limited strictly to the two provided reference dimensions.

## 📝 Tutor Feedback

> "Good effort. The submission meets basic requirements but lacks depth or polish. Refine your work for better results."

**Score: 3/5**

The feedback highlighted that the core requirements were met, but the implementation could have benefited from additional refinement and attention to detail.

This assignment reinforced that getting the basic structure working is only the first stage of frontend development. Matching a reference design effectively also requires careful attention to:

* Spacing
* Typography
* Element sizing
* Alignment
* Responsive behavior
* Visual hierarchy
* Overall polish

## 🔍 Key Takeaway

This project taught me that **functional CSS and polished CSS are not necessarily the same thing**.

A layout can have the correct grid structure and still fall short of the reference design because of small differences in spacing, sizing, typography, or alignment.

The 3/5 assessment was a useful reminder to spend more time comparing the final implementation against the original design instead of stopping once the general layout works.

## 🚀 Future Improvements

Given more refinement time, I would focus on:

* More precise spacing and sizing
* Closer comparison against the reference design
* Better handling of intermediate viewport sizes
* More detailed responsive adjustments
* Refining typography and visual hierarchy
* Improving the overall visual polish of individual cards

## 👤 Author

**Brian Ngari**

TechCrush Frontend Development Bootcamp
