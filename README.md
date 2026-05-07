# 📺 Dynamic YouTube Feed Integration

A lightweight, high-performance web component that fetches and displays live video content from a specific YouTube channel using the **YouTube Data API v3**.

---

### 🚀 Key Features
- **Live Data Fetching:** Utilizes `Async/Await` and the `fetch` API to retrieve real-time video metadata.
- **Dynamic DOM Manipulation:** Efficiently renders video iframes using JavaScript's `.filter()` and `.map()` methods to ensure only video content is displayed[cite: 3].
- **Error Handling:** Includes a robust `try/catch` block to handle API status errors and provide user-friendly feedback in case of failure[cite: 3].
- **Automated Refresh:** Features a background interval logic to automatically refresh the feed every 24 hours without requiring a page reload[cite: 3].
- **Responsive Design:** Styled with CSS Flexbox to ensure the video grid remains clean and accessible across different screen sizes[cite: 3].

---

### 🛠️ Tech Stack
- **Language:** JavaScript (ES6+).
- **API:** Google YouTube Data API v3.
- **Frontend:** HTML5, CSS3 (Flexbox/Shadows).

---

### 💡 Why I Built This
This project was designed to solve a common frontend challenge: integrating third-party dynamic content while maintaining page speed and security. It demonstrates my proficiency in handling JSON responses and managing API keys in a client-side environment[cite: 3].

---

### 📂 How to Use
1. Clone the repository.
2. Replace the `API_KEY` and `CHANNEL_ID` constants in the script with your own credentials from the Google Cloud Console[cite: 3].
3. Open `index.html` in any modern browser.

---

### 📫 Connect with Me
- **Portfolio:** [asrarfedlu-portfolio-web.netlify.app](https://asrarfedlu-portfolio-web.netlify.app)
- **LinkedIn:** [Asrar Fedlu Kedir](https://www.linkedin.com/in/asrar-fedlu-kedir-23862520a)
