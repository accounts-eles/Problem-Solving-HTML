Learning Activity: Interactive Learning Objects

A responsive, accessible, and lightweight interactive web application designed to teach learners about the benefits of interactive learning objects through hands-on practice.

Overview

This project is a self-contained "learning object" about learning objects. It utilizes a modern UI with a deep navy and teal palette, featuring an accordion-style interface that guides users through four distinct educational steps, including knowledge checks and reflective practice.

Features

Interactive Accordion: Organised learning flow that expands one section at a time to reduce cognitive load.

Multiple Interaction Types:

Single-choice radio buttons.

Multiple-choice checkboxes.

Free-text reflection areas.

Action planning inputs.

Immediate Feedback: Real-time feedback loops that explain why an answer is correct or incorrect.

Responsive Design: A two-column layout on desktop with a sticky "Cheat Sheet" sidebar that collapses into a single column for mobile devices.

Accessibility Focused: Uses semantic HTML (<main>, <section>, <aside>, <button>), ARIA labels, and keyboard-accessible triggers.

Technical Details

Architecture

Single-File Build: All HTML, CSS, and JavaScript are contained within a single .html file for easy distribution and deployment.

Styling: Built with CSS Custom Properties (Variables) for consistent branding. It uses a modern CSS Grid and Flexbox layout.

State Management: Simple JavaScript-driven state handling for the accordion and feedback mechanisms (does not require external libraries or frameworks).

CSS Custom Properties

The design uses a specific brand palette:

--ink: #1f2a52 (Deep Navy)

--teal: #00bec7 (Bright Teal)

--mist: #d2f0f0 (Pale Aqua)

--steel: #abb5bf (Soft Grey)

Key Functions

showFeedback(id, type, html): Dynamically updates the UI to provide positive (good) or corrective (warn) feedback to the learner.

triggers.forEach: Manages the accordion logic, ensuring that only one panel is open at a time to maintain focus.

Usage

To use this activity in a learning management system (LMS) or as a standalone resource:

Copy the HTML code.

Save it as index.html.

Open the file in any modern web browser.

Browser Support

The application is compatible with all modern browsers (Chrome, Firefox, Safari, Edge) that support CSS Grid and ES6 JavaScript.
