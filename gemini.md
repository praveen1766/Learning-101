# AI Learning Portal for Andhra Pradesh - Gemini Instructions

## Project Overview
This is a static HTML website hosted on GitHub Pages, designed as an interactive learning portal for non-technical people in Andhra Pradesh. The portal uses a "spoon-fed" approach with progressive cue cards to teach IT and AI basics, incorporating local Andhra Pradesh examples for relatability.

**Live Site:** https://praveen1766.github.io/Learning-101/

## Current Project Structure
- **Main File:** `index.html` - Portal homepage with expandable category sections
- **Sections/Folders:**
  - `basic-computer-skills/` - Cards 1, 2, 3
  - `internet-fundamentals/` - Cards 1, 2
  - `programming-basics/` - Cards 1, 2
  - `data-databases/` - Cards 1, 2
  - `ai-basics/` - Cards 1, 2
  - `ai-tools/` - Cards 1, 2
  - `job-prep/` - Cards 1, 2

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
- Max-width 800px for cards, centered with flex
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
1. **Create Card File:** Copy template, customize content for the topic
2. **Update Index:** Add card link in the relevant `<details>` section
3. **Update Navigation:** Modify prev/next links in adjacent cards
4. **Test Locally:** Ensure animations, quiz, and links work
5. **Commit & Push:** Use descriptive commit messages

## Current Progress & Next Steps
- **Completed:** Basic Computer Skills Cards 1-3
- **Next:** Add Card 3 to Internet Fundamentals, then continue sequentially through sections
- **Goal:** Build comprehensive progressive learning path

## Important Notes
- Maintain consistent formatting and colors
- Use local Andhra Pradesh examples in all content
- Ensure mobile responsiveness
- Keep animations subtle and non-distracting
- Follow the established file naming: `section/cardX.html`

This ensures Gemini can generate new cards that seamlessly integrate with the existing design and content style.</content>
<parameter name="filePath">/Users/praveenmandadi/development/Learning-101/gemini.md