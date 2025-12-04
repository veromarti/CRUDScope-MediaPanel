# CRUDScope – HTML MediaPanel

CRUDScope is a learning-oriented HTML project focused on practicing semantic structure, multimedia integration, tables, forms, and basic layout techniques without using JavaScript.  
The page simulates a CRUD-style interface for Artistic Swimming hybrids creation, allowing users to “add” hybrids, display them in a table, and showcase multimedia content.

---

## Project Overview

The purpose of this project is to:

- Practice semantic HTML structure.
- Use multimedia elements such as images, audio, and embedded video.
- Build a readable and organized form using native HTML elements.
- Create a visually structured table representing hybrid routines.
- Explore layout techniques without Flexbox or Grid (using float, table/table-cell, and block logic).
- Implement meaningful metadata, icons, typography, and a simple footer with contact information.

This project **does not use JavaScript**, so any CRUD behavior is simulated visually.

---

## HTML Tag Research

Below is a categorized list of the main tags used in the project, with short descriptions.

---

### **1. Document Structure**

**Tags:** `html`, `head`, `body`, `meta`, `title`, `base`, `link`

- **Purpose:** Define the global structure of the document and link external resources.
- **Typical use case:** Setting metadata, loading fonts and stylesheets, defining a base URL for relative paths.

---

### **2. Semantic Layout Tags**

**Tags:** `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `address`

- **Purpose:** Provide meaningful, descriptive structure for each part of a webpage.
- **Typical use case:**  
  - `header` for titles and navigation  
  - `main` for main content  
  - `section` for grouped thematic areas  
  - `article` for independent content blocks  
  - `aside` for tips or secondary info  
  - `footer` for contact, legal text, and site metadata  
  - `address` for author or organization info

---

### **3. Non-Semantic Tags**

**Tags:** `div`, `span`

- **Purpose:** Structure content when no semantic meaning is required.
- **Typical use case:**  
  - `div` for grouping layout elements  
  - `span` for inline highlighting  
- These tags do not communicate meaning to search engines or assistive technologies.

---

### **4. Text and Inline Formatting**

**Tags:** `h1`, `h2`, `h3`, `p`, `strong`, `em`, `u`, `mark`, `abbr`

- **Purpose:** Provide readable content and enhance text meaning.
- **Typical use case:**  
  - Headings for structure  
  - `p` for paragraphs  
  - `strong` / `em` for emphasis  
  - `u` for underlined text  
  - `mark` for highlights  
  - `abbr` to display an abbreviation with a tooltip explanation  

---

### **5. Tables**

**Tags:** `table`, `thead`, `tbody`, `tr`, `th`, `td`

- **Purpose:** Display structured data in rows and columns.
- **Typical use case:** A list of hybrid routines with routine type, category, audio, and actions.

---

### **6. Forms**

**Tags:** `form`, `label`, `input`, `select`, `option`, `button`

- **Purpose:** Collect user input.
- **Typical use case:** Simulated creation of hybrid routines with fields for routine type, category, hybrid code, duration, and music file upload.

---

### **7. Multimedia**

**Tags:** `img`, `audio`, `source`, `iframe`

- **Purpose:** Insert images, audio files, and embedded videos.
- **Typical use case:**  
  - `img` to display GIF animations  
  - `audio` to preview MP3 files  
  - `iframe` to display embedded YouTube videos  
- Multimedia tags improve user experience compared to linking external files.

---

## Semantic vs. Non-Semantic Tags

### ✔ **Semantic Tags**
Tags whose names describe their purpose and meaning.

**Examples:**  
`header`, `nav`, `main`, `section`, `article`, `footer`

**When to use:**  
Use semantic tags when the element has a meaningful role in the document. They improve accessibility and SEO.

---

### ✔ **Non-Semantic Tags**
Tags that do not communicate meaning on their own.

**Examples:**  
`div`, `span`

**When to use:**  
Use them when no semantic tag fits the content or when grouping elements solely for styling or layout.

---

## Focus on Less Common Tags

### **1. `<base>`**
- Defines a base URL for all relative links on the page.
- **Effect:**  
  All `href` or `src` attributes without an absolute path automatically use the base URL.
- **Use case:**  
  Useful in GitHub Pages deploys to avoid broken paths.

---

### **2. `<abbr>`**
- Represents an abbreviation or acronym.
- The `title` attribute displays the full meaning on hover.
- **Use case example:**  
  `<abbr title="Create, Read, Update, Delete">CRUD</abbr>`

---

### **3. `<time>`**
- Represents a date or time value in a machine-readable format.
- **Use case:**  
  Enhances metadata for articles, posts, events, etc.  
  *(Used optionally depending on the project.)*

---

### **4. Multimedia Tags Advantages**
- Provide native browser controls.
- Improve accessibility and user experience.
- Allow playback without external applications.
- Load faster and safer than linking to external files.

Examples:  
`<audio controls>`, `<video>`, `<iframe>`, `<img>`

---

## References

- MDN Web Docs — https://developer.mozilla.org/
- W3C HTML Living Standard — https://html.spec.whatwg.org/
- Google Fonts Documentation
- Font Awesome Icons Library
- YouTube Embed Guidelines
- Pexels Licensing and Embedding Guidelines

---

## ✔ Author

**Created by:** Verónica Martínez Cadavid  
Project: *Mermaid Code – CRUDScope MediaPanel*  
2025

