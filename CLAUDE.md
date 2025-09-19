# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This repository focuses on The Odin Project's sign-up form project located in `project-sign-up-form/`. All development work should be concentrated on this project.

## Project Structure

**Main Project Files:**
- **`project-sign-up-form/sign-up-form.html`** - Main HTML file for the sign-up form
- **`project-sign-up-form/styles.css`** - CSS styling for the form and layout
- **`project-sign-up-form/images/`** - Background image and logo assets
- **`project-sign-up-form/fonts/`** - Custom web fonts (Faculty Glyphic, Ribeye)

## Development Approach

This is a static HTML/CSS project with no build process. Open `sign-up-form.html` directly in a browser for testing.

## Architecture

### Layout Structure
- **Left Sidebar (33.33%):** Hero image with overlaid logo and credit text
- **Main Content (66.67%):** Form content with heading, subtext, and sign-up form
- **Responsive:** Switches to column layout on mobile (768px breakpoint)

### Typography
- **Faculty Glyphic:** Primary font for body text, form inputs, and labels
- **Ribeye:** Decorative font for main headings and form title
- Both fonts loaded via `@font-face` from local WOFF/WOFF2 files

### Form Features
- **Validation States:** Visual feedback for valid/invalid inputs using CSS pseudo-classes
- **Floating Labels:** Labels appear above inputs when focused or filled
- **Input Types:** Text, email, tel, password with appropriate validation
- **Required Fields:** First name, last name, email, password, confirm password

### Color Scheme
- **Primary Green:** #8BC34A (focus states, valid inputs)
- **Teal:** #00796B (submit button, links)
- **Error Red:** #b92326 (invalid inputs)
- **Text:** #455A64 (main text), #333 (headings)

### Testing
Open `project-sign-up-form/sign-up-form.html` in a browser. Test form validation by entering valid/invalid data and test responsive behavior by resizing the window.