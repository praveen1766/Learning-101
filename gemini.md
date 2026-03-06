# AI Learning Portal for Andhra Pradesh - Gemini Instructions

## Project Overview
This is a static HTML website hosted on GitHub Pages, designed as an interactive learning portal for non-technical people in Andhra Pradesh. The portal uses a "spoon-fed" approach with progressive cue cards to teach IT and AI basics, incorporating local Andhra Pradesh examples for relatability.

**Live Site:** https://praveen1766.github.io/Learning-101/

## Current Project Structure
- **Main File:** `index.html` - Portal homepage with expandable category sections
- **Sections/Folders:**
  - `basic-computer-skills/` - Cards 1, 2, 3, 4, 5, 6, 7
  - `internet-fundamentals/` - Cards 1, 2, 3
  - `programming-basics/` - Cards 1, 2, 3
  - `data-databases/` - Cards 1, 2, 3
  - `ai-basics/` - Cards 1, 2, 3
  - `ai-tools/` - Cards 1, 2, 3
  - `job-prep/` - Cards 1, 2, 3

## Design Guidelines
### Colors
- Primary Blue: #2563eb
- Dark Blue: #1e3a8a
- Light Blue: #eff6ff, #f0f9ff
- Text: #333, #4b5563
- Background: #f0f2f5

### Fonts
- Font Family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- Headings: Bold, color #1e3a8a or #2563eb
- Body Text: Line-height 1.6, color #4b5563

### Layout
- Card-based design with white backgrounds, border-radius 12px, box-shadow 0 4px 12px rgba(0,0,0,0.1)
- Max-width: 800px for cards, centered with flex
- Animations: fadeIn for cards, slideIn for storyboard steps
- Icons: Font Awesome 6, size 48px, color #2563eb, width 70px container

### Interactive Elements
- Expandable `<details>` sections on index.html
- Toggle button for expand/collapse all categories
- Quiz with JavaScript for feedback

## Card Template Structure
Each card follows this consistent format:

### HTML Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Section Name - Card X: Title</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        /* CSS as in existing cards */
    </style>
</head>
<body>
    <div class="card">
        <h1><i class="fas fa-icon"></i> Card X: Title</h1>
        <p>Intro with Andhra Pradesh example...</p>
        
        <div class="storyboard">
            <div class="story-step">
                <div class="icon"><i class="fas fa-step-icon"></i></div>
                <div class="step-content">
                    <h3>Step Title</h3>
                    <p>Step description...</p>
                </div>
            </div>
            <!-- 2-3 more steps -->
        </div>
        
        <div class="terms-section">
            <h3>Key Terms</h3>
            <ul>
                <li><strong>Term:</strong> Definition</li>
            </ul>
        </div>
        
        <div class="quiz-section">
            <h3>Quick Quiz</h3>
            <p>Question?</p>
            <select id="q1">
                <option value="none">Select answer</option>
                <option value="correct">Answer</option>
            </select>
            <button class="btn" onclick="checkAnswer()">Check Answer</button>
            <div id="quiz-result"></div>
        </div>
        
        <div class="nav">
            <a href="card-prev.html">Previous</a>
            <a href="card-next.html">Next</a>
            <a href="../index.html">Home</a>
        </div>
    </div>
    
    <script>
        function checkAnswer() {
            // JS logic for quiz
        }
    </script>
</body>
</html>
```

### Content Guidelines
- **Icons:** Relevant Font Awesome icons for each step
- **Examples:** Always include Andhra Pradesh/local analogies (farming, markets, etc.)
- **Storyboard:** 3-4 steps with clear, simple explanations
- **Terms:** 4-5 key terms with definitions
- **Quiz:** Multiple choice with JS feedback (green/red colors)
- **Navigation:** Previous/Next/Home links with icons

## Instructions for Adding New Cards
1. **Review Existing Content:** Before generating new cards, review all existing cards in the same section to understand the progression and avoid repetition
2. **Ensure Incremental Learning:** New cards should build upon previous cards in the section, introducing concepts at the appropriate difficulty level
3. **Maintain Consistency:** Honor the content style, examples, and difficulty progression established in existing cards for that section
4. **Create Card File:** Copy template, customize content for the topic following the established patterns
5. **Update Index:** Add card link in the relevant `<details>` section
6. **Update Navigation:** Modify prev/next links in adjacent cards
7. **Update Progress:** Update the "Current Project Structure" and "Current Progress & Next Steps" sections in this gemini.md file to reflect the new card
8. **Test Locally:** Ensure animations, quiz, and links work
9. **Commit & Push:** Use descriptive commit messages including the updated gemini.md

## Current Progress & Next Steps
- **Completed:** Basic Computer Skills section is now complete up to Card 7.
- **Next:** Move to the next section, "Internet Fundamentals", and add more advanced cards.
- **Goal:** Build comprehensive progressive learning path

## Important Notes
- **Honor Existing Content:** When generating new cards, always review and build upon the content, style, and progression of existing cards in the same section
- **Incremental Progression:** Ensure new content is appropriately advanced from previous cards, maintaining the "spoon-fed" learning approach
- Maintain consistent formatting and colors
- Use local Andhra Pradesh examples in all content
- Ensure mobile responsiveness
- Keep animations subtle and non-distracting
- Follow the established file naming: `section/cardX.html`

This ensures Gemini can generate new cards that seamlessly integrate with the existing design and content style.