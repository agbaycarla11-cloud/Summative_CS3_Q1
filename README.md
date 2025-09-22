# Summative_CS3_Q1
A 5 page website about my interest/hobbies.

## Overview
This project is a **static personal website** built using **HTML and CSS**.  
It contains multiple pages showcasing personal details, hobbies, and interests, styled consistently through a single CSS file.

---

## Project Structure
```
Personal_Interest_Website/
│── index.html        # Homepage
│── about.html        # About page
│── contact.html      # Contact page
│── gallery.html      # Gallery page
│── interests.html    # Interests page
│── styles.css        # Global CSS stylesheet
│── images/           # Image assets
     ├── books1.jpg
     ├── books2.jpg
     ├── crochet1.jpg
     ├── crochet2-art.jpg
     ├── show1.jpg
     ├── show2.jpg
     └── student.jpg
```

---

## 🌐 Website Pages

### 1. **Home Page** (`index.html`)
- Acts as the **main entry point** of the website.
- Includes:
  - Website navigation bar.
  - Welcome introduction.
  - Links to other pages.

### 2. **About Page** (`about.html`)
- Describes background information about the site owner.
- May include text, an image, and short bio.

### 3. **Contact Page** (`contact.html`)
- Provides ways to get in touch (e.g., email form, details).
- Includes basic layout for user interaction.

### 4. **Gallery Page** (`gallery.html`)
- Displays a collection of images.
- Images are stored inside `/images/`.

### 5. **Interests Page** (`interests.html`)
- Lists hobbies and interests (e.g., books, movies, crochet).
- Each interest is illustrated with images and styled text.

---

## 🎨 CSS Styling (`styles.css`)

The entire website is styled using a **single external CSS file**: `styles.css`.

### Global Styles
- Applies font, background, and text formatting for all pages.
- Example:
  - `body { ... }` → sets font, margin, padding, and background color.

### Navigation Bar
- Classes used for navigation menu:
  - `.navbar` – container for the navigation bar.
  - `.navbar a` – styles links inside the navigation.
  - `.active` – highlights the current page link.

### Page Layout
- Common **section and container classes**:
  - `.content` – main wrapper for page text.
  - `.container` – groups text and images.
  - `.gallery` – grid layout for images on the gallery page.

### Images
- `.gallery img` – sets width, height, margin, and border.
- `.profile` – specific styling for personal/portrait images.

### Text Formatting
- `h1, h2, h3` – styled with specific font size and alignment.
- `.highlight` – used to emphasize certain words or phrases.

---

## Images
All images are stored in the `/images/` folder.  
Examples:
- `student.jpg` → Profile/portrait photo.
- `books.jpg` → Represents reading interest.
- `crochet.jpg` → Represents crochet hobby.
- `gallery-art.jpg` → Used in the gallery.

---

## How to Run the Project
1. Download and extract the project folder.
2. Open `index.html` in any web browser.
3. Navigate using the menu to explore different pages.

---

## Notes for Maintenance
- To add new pages:
  1. Create a new `.html` file.
  2. Add a link in the navigation bar (`<nav>`).
  3. Update `styles.css` if new styling is needed.
- To replace images:
  - Save the new image inside the `/images/` folder.
  - Update the `<img src="images/...">` path in the HTML files.