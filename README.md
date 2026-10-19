# Single-Page CV Website & Portfolio

**Author:** Pol Martínez i Aguilera  
**Degree:** Bachelor's Degree in Computer Engineering (3rd Year)  
**Institution:** University of Girona (UdG)  

* **Figma Project Link:** [View Figma Design](https://www.figma.com/design/xVsSS9bvwbwatxYF6XTOfc/Untitled?node-id=7-8&t=NLEOScK2dMYIVweS-1)  
* **Live Website (GitHub Pages):** [View Live CV Web](https://u6103249.github.io/cv-hypermedia/)  

---

## 1. Project Analysis

### User Profile (User Persona)

* **Name:** Sarah Jenkins  
* **Role:** Technical Recruiter / Hiring Manager at a software engineering company.  
* **Goals:**  
  * Quickly assess the candidate's academic background, technical skills, and contact details without wasting time.  
  * Check the specific coursework and subjects being taken at the University of Girona (UdG).  
  * Easily find direct links to the candidate's GitHub and LinkedIn profiles to inspect practical projects.  
* **Pain Points:**  
  * Overwhelmed by cluttered, multi-page resumes that lack visual structure.  
  * Unclear distinction between actual programming languages known and general soft skills.  
* **Expectations:** A clean, responsive single-page resume formatted in structured UI cards with immediate access to contact details and a PDF download button.  

---

### Information Architecture

To ensure the website is easy and fast to scan for recruiters, the page is organized into a clean two-column layout featuring key interactive elements:

The left column functions as a fixed personal sidebar. It contains my profile photograph, academic status at UdG, contact information (email and phone), interactive action buttons for **GitHub** and **LinkedIn**, language proficiencies, and location details. By placing the GitHub and LinkedIn buttons inside this persistent sidebar, recruiters can click at any time to open my external profiles in a new tab without losing their place on the page.

The right column hosts the main content of the resume. It opens with a dark blue header displaying my full name, title (*Computer Engineering Student*), and a prominent **Download CV** button designed to allow immediate downloading of a PDF copy directly via HTML. Right below the header, an 'About Me' card provides a brief executive summary of my background and goals.

The rest of the content is divided into three distinct UI cards: 'Skills' (separating personal soft skills from technical skills like C++, Python, Java, and SQL), 'Education' (highlighting my Computer Engineering degree at UdG and Technological Baccalaureate), and 'Experience & Projects' (emphasizing my supervisory role at Condis Supermercats, tutoring experience, and academic software projects).

---

### Visual Design

The visual design adopts a modern, clean, and tech-oriented aesthetic suitable for a computer engineering profile. The color scheme relies on a high-contrast combination: a deep slate blue for the sidebar and header card, a very light gray background for the page, and clean white card containers to maximize text legibility.

Typography utilizes a crisp sans-serif typeface (Inter) for excellent readability on digital displays. Typographic hierarchy is established using contrasting font weights and sizes to clearly distinguish main section headings from body descriptions and dates.

Structural UI elements rely on cards with rounded corners (12px to 16px radius) and subtle borders. Micro-interactions are built directly into the HTML and CSS: the **GitHub** and **LinkedIn** buttons feature smooth hover effects (*While Hovering*) to indicate clickability, and the **Download CV** button uses an accent highlight color so users immediately recognize it as a primary call to action.
