# Smart-Guide 🌟

A curated directory of famous YouTube channels, Facebook pages, and TikTok accounts categorized by type (e.g., Education, Entertainment, Tech). Built with modern web technologies for a responsive and user-friendly experience.

![Smart-Guide Preview](https://via.placeholder.com/800x400?text=Smart-Guide+Preview) *(Replace with your actual screenshot later)*

## Features ✨
- **Categorized Listings**: Browse platforms by type (e.g., "Tech Reviewers", "Cooking Channels").
- **Search & Filter**: Find influencers quickly with keywords or tags.
- **Responsive Design**: Works on mobile, tablet, and desktop.
- **Dark/Light Mode**: Toggle for user preference (optional, if implemented).
- **Embedded Previews**: Watch YouTube/TikTok clips directly (optional).

## Technologies Used 🛠️
- **Frontend**: HTML5, CSS3, jQuery
- **CSS Framework**: [Tailwind CSS](https://tailwindcss.com/) (utility-first)
- **Deployment**: Hosted on GitHub Pages (free)

## Live Demo 🚀
[View Live Site](https://your-username.github.io/smart-guide/)  
*(Replace with your GitHub Pages URL after deployment)*

## How to Use locally 💻
1. **Clone the repository**:
   ```sh
   git clone https://github.com/your-username/smart-guide.git
   cd smart-guide


## Project Structure 📂

### Key Files Explained:
1. **`index.html`**
    - Uses Tailwind CDN (or links to local `tailwind.css`)
    - Imports jQuery (CDN/local) and `script.js`
    - Contains the main layout (navbar, category sections, etc.)

2. **`js/data.js`** *(Example format)*
   ```javascript
   const channels = {
     youtube: [
       { 
         name: "TechTok", 
         url: "https://youtube.com/@techtok",
         category: "Technology",
         subscribers: "1.2M"
       }
     ],
     tiktok: [...]
   };

### Key Customizations for Your Project:
1. **Data Storage**:
    - If you’re using a static JSON file to store channel listings (recommended), add a note like:
      ```markdown
      ## Data Format (JSON Example)
      ```json
      {
        "categories": [
          {
            "name": "Tech",
            "youtube": ["@MKBHD", "@LinusTechTips"],
            "tiktok": ["@tech_tok"]
          }
        ]
      }
      ```
      ```
2. **Tailwind Setup**:
    - If you installed Tailwind via npm (not CDN), add build instructions:
      ```markdown
      ## Build Tailwind CSS
      ```sh
      npm install
      npx tailwindcss -i ./src/input.css -o ./css/styles.css --watch
      ```
      ```

3. **Screenshots**:
    - Replace the placeholder image with a real screenshot after development (`/assets/preview.png`).

Let me know if you’d like help structuring the HTML/jQuery code or Tailwind config!