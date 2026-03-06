# AI Learning Portal for Andhra Pradesh

## Project Overview
This is a static HTML website hosted on GitHub Pages, designed as an interactive learning portal for non-technical people in Andhra Pradesh. The portal uses a "spoon-fed" approach with progressive cue cards to teach IT and AI basics, incorporating local Andhra Pradesh examples for relatability.

## Live Site
The live version of this project is hosted on GitHub Pages and can be accessed here:
**[https://praveen1766.github.io/Learning-101/](https://praveen1766.github.io/Learning-101/)**

## Project Structure
The project is organized into sections, with each section containing a series of learning cards.

- **Main File:** `index.html` - The portal homepage with expandable category sections.
- **Sections/Folders:**
  - `basic-computer-skills/`
  - `internet-fundamentals/`
  - `programming-basics/`
  - `data-databases/`
  - `ai-basics/`
  - `ai-tools/`
  - `job-prep/`

Each section folder contains `cardX.html` files, representing the progressive learning steps for that topic.

## Design Guidelines

### Colors
- **Primary Blue:** `#2563eb`
- **Dark Blue:** `#1e3a8a`
- **Light Blue:** `#eff6ff`, `#f0f9ff`
- **Text:** `#333`, `#4b5563`
- **Background:** `#f0f2f5`

### Fonts
- **Font Family:** 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- **Headings:** Bold, with colors `#1e3a8a` or `#2563eb`
- **Body Text:** Line-height of 1.6, color `#4b5563`

### Layout
- The portal uses a card-based design with white backgrounds, rounded corners (`border-radius: 12px`), and a subtle shadow (`box-shadow: 0 4px 12px rgba(0,0,0,0.1)`).
- Cards have a maximum width of 800px and are centered.
- Animations are used for fading in cards and sliding in storyboard steps.
- Icons are from Font Awesome 6.

## How to Contribute (Instructions for Adding New Cards)
This project is designed to be easily extensible. To add a new learning card, please follow these steps:

1.  **Review Existing Content:** Before creating a new card, review the existing cards in the same section to understand the learning progression and avoid repetition.
2.  **Ensure Incremental Learning:** New cards should build upon the concepts introduced in previous cards in that section.
3.  **Maintain Consistency:** Adhere to the established content style, use of local Andhra Pradesh examples, and difficulty level.
4.  **Create Card File:** Copy the structure from an existing card or use the template provided in `gemini.md`. Customize the content for the new topic.
5.  **Update Index Page:** Add a link to your new card in the corresponding section of the `index.html` file.
6.  **Update Navigation:** Modify the `previous`/`next` navigation links in the adjacent cards to include your new card.
7.  **Update `gemini.md`:** Reflect the addition of the new card in the `gemini.md` file to keep the project documentation up to date.
8.  **Test Locally:** Ensure all links, animations, and interactive elements (like the quiz) are working correctly.
9.  **Commit & Push:** Use a descriptive commit message for your changes.
