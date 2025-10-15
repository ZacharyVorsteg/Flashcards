# ✨ Flashcards Study App

A beautiful, simple, and effective flashcard study tool with quiz mode and smart randomization.

## 🌟 Features

- **📖 Study Mode** - Flip cards to reveal answers with smooth 3D animations
- **🎯 Quiz Mode** - Multiple choice questions with instant feedback
- **🔀 Smart Randomization** - Never see the same card twice until you've studied them all
- **📊 Real-time Stats** - Track your progress, score, and streak
- **📁 Multiple Formats** - Upload .txt, .docx, or .json files
- **📱 Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- **🎨 Premium UI** - Beautiful gradients, smooth animations, and modern design
- **🔄 Dynamic Content Scaling** - Automatically adjusts font size and card height based on content complexity
- **📏 Smart Text Handling** - Perfect word wrapping and scrolling for complex, lengthy content

## 🚀 How to Use

1. Open the app in your browser
2. Upload your flashcards file
3. Choose between Study Mode or Quiz Mode
4. Start learning!

### 📝 File Format

**Text File (.txt)** - Easiest format:
```
What is the capital of France? | Paris
Who wrote Romeo and Juliet? | William Shakespeare
2 + 2 = ? | 4
```

**JSON File (.json)**:
```json
[
  {"question": "What is the capital of France?", "answer": "Paris"},
  {"question": "Who wrote Romeo and Juliet?", "answer": "William Shakespeare"}
]
```

**Word Document (.docx)** - Same format as text files

## 🎮 How It Works

- **Study Mode**: Click cards to flip them and see the answer. Use Previous/Next buttons to navigate, or Shuffle to randomize.
- **Quiz Mode**: Select the correct answer from multiple choices. Get instant feedback and track your streak!
- **Progress Tracking**: Watch your progress bar fill up as you study more cards.
- **No Repeats**: The app ensures you won't see the same card twice until you've gone through all of them.

## 🔄 Dynamic Content Scaling

The app intelligently adapts to your content:

- **Short content (< 50 chars)**: Large, easy-to-read text
- **Medium content (50-150 chars)**: Optimally balanced size
- **Long content (150-300 chars)**: Smaller text for readability
- **Very long content (> 300 chars)**: Compact text with smooth scrolling

**Card height automatically adjusts** to accommodate complex answers and questions, ensuring everything is visible and readable without awkward spacing.

### Complex Content Examples

The app handles everything from simple facts:
```
Capital of France | Paris
```

To detailed explanations:
```
What is quantum entanglement? | Quantum entanglement is a physical phenomenon that occurs when a pair or group of particles is generated, interact, or share spatial proximity in a way such that the quantum state of each particle cannot be described independently of the state of the others...
```

See `complex-flashcards-example.txt` for a demonstration file with varying content complexity.

## 💡 Tips

- Start with Study Mode to familiarize yourself with the content
- Switch to Quiz Mode to test your knowledge
- Build up your streak for motivation!
- The app remembers your current session, so take breaks when needed
- Don't worry about content length - the app adapts automatically!
- Mix short and long content for varied studying experiences

## 🛠️ Technical Details

- Pure HTML, CSS, and JavaScript - no build process required
- Uses Mammoth.js for .docx file parsing
- Fully client-side - your data never leaves your device
- Works offline after initial load

## 📦 Deployment

This app can be deployed anywhere static sites are supported:
- Netlify
- Vercel
- GitHub Pages
- Any web server

Simply upload the `index.html` file and you're done!

---

Made with ❤️ for effective studying
