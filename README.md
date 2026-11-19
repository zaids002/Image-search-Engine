# Image Search Engine

A sleek, responsive web application that lets users search and browse high-resolution images powered by the **Unsplash API**. Built with pure HTML, CSS, and Vanilla JavaScript.

## Features

- **Keyword Image Search:** Search for any topic and fetch matching photos in real time from Unsplash.
- **Grid Gallery Layout:** Displays search results in a clean 3-column grid with uniform image sizing.
- **Pagination ("Show More"):** Loads 12 images per page and lets users seamlessly load additional batches of results.
- **Direct Source Links:** Clicking any image opens the original photo page on Unsplash in a new browser tab.

## Tech Stack

- **HTML5** – Semantic markup and search form structure
- **CSS3** – Custom styling, Flexbox alignment, and CSS Grid gallery layout
- **JavaScript (ES6+)** – `fetch` API with `async/await`, dynamic DOM manipulation, and pagination state
- **Unsplash API** – Image search data and photo URLs

## Project Structure

```text
├── index.html   # Main HTML page and search interface
├── style.css    # Page styling, theme colors, and 3-column grid layout
└── script.js    # Unsplash API integration, image rendering, and pagination logic
```

## Getting Started

### Prerequisites

You need a free **Access Key** from the [Unsplash Developers](https://unsplash.com/developers) portal to run this project locally.

### Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/zaids002/image-search-engine.git](https://github.com/zaids002/image-search-engine.git)
   cd image-search-engine
   ```

2. **Add your Unsplash API key:**
   Open `script.js` and replace the `accessKey` placeholder with your own Unsplash Access Key:
   ```javascript
   const accessKey = "YOUR_UNSPLASH_ACCESS_KEY";
   ```

3. **Run the project:**
   Open `index.html` directly in your web browser, or launch it using a local development server (such as the **Live Server** extension in VS Code).

## Author

- **Zaid Syed** – [@zaids002](https://github.com/zaids002)

## Acknowledgments

- Powered by the [Unsplash API](https://unsplash.com/developers).
