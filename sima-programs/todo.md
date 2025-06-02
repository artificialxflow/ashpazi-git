To-Do List: Mobile Web Page Design
This document outlines the requirements for designing and implementing a responsive mobile web page.

Project Goal
Create a responsive mobile web page for displaying a list of TV programs, as per the provided design sketch. The page should be optimized for mobile devices and support Right-to-Left (RTL) text direction for Persian content.

Technical Specifications
Technologies: HTML, CSS (pure CSS for specific styles), Bootstrap 5.

Page Dimensions: The design should be optimized for a mobile viewport of approximately 412px width by 917px height, but must be fully responsive to adapt to various screen sizes.

Text Direction: Right-to-Left (RTL) to accommodate Persian language content. Ensure proper use of Bootstrap's RTL utilities.

Page Structure and Content
The page consists of three main sections: a Header, a Main Content area, and a Bottom Navigation Bar.

1. Header Section
Appearance: A pink/red colored bar at the top with rounded bottom corners.

Elements (from right to left for RTL layout):

Right Side: A simple hamburger menu icon (can be an SVG or a basic icon representation).

Center: The text "برنامه های سیما" (TV Programs) with appropriate font size and styling.

Left Side: A back arrow icon (←) (can be an SVG or a basic icon representation).

2. Main Content Section (Program Cards Grid)
Layout: A two-column grid displaying program cards.

Each Card:

Image: Use an <img> tag. The suggested dimensions for the image are 180px by 180px.

Placeholder: The src attribute for the image should be left as an empty placeholder (e.g., src="").

Alt Text: The alt attribute should contain the program's title (e.g., alt="به خانه برمی‌گردیم").

User Action: The user will manually insert the actual image URLs into the src attribute after generation.

Program Title: Text displayed directly below the image. The titles for the cards, from top-left to bottom-right, are:

"به خانه برمی گردیم"

"آشپزی با مامان"

"بهونه آشپزی"

"شبکه نسیم"

"آشپزی"

"پخت و پند"

Styling: Cards should have a visual appearance similar to the design sketch, including rounded corners and a subtle shadow effect.

3. Bottom Navigation Bar
Appearance: A horizontal pink/red colored bar at the bottom with rounded top corners.

Elements: It should contain 5 icons.

Icon Type: Use <img> tags for icons.

Placeholder: The src attribute for each icon should be left as an empty placeholder (e.g., src="").

Alt Text: The alt attribute should describe the icon (e.g., alt="Person Icon").

User Action: The user will manually insert the actual PNG icon URLs into the src attribute after generation.

Icons (from right to left for RTL layout):

Person Icon

Play/Calendar Icon

Home Icon

Heart Icon

Book Icon

General Implementation Notes
Bootstrap Usage: Leverage Bootstrap classes extensively for responsive behavior, grid layout, and foundational styling.

Custom CSS: Apply pure CSS for specific styling elements not directly covered by Bootstrap (e.g., exact color shades, custom rounded corners, subtle shadows, specific element spacing).

Clarity for Manual Additions: Clearly indicate in HTML comments where the user needs to manually add image src URLs for program cards and navigation icons.

Visual Fidelity: Ensure the spacing, dimensions, and overall visual presentation closely match the provided mobile design sketch.

Expected Output
A single, complete HTML file containing all necessary structure.

Embedded CSS (<style> tags within <head>) for custom styling.

All required Bootstrap classes applied for responsiveness and RTL.

Clear HTML comments indicating where image/icon src attributes need to be filled in by the user.