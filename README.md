# Greenwood Community Library Website Enhancement

## Project Overview
This project enhances the **Greenwood Community Library** website to make it more engaging for visitors.  
The site already has four sections: Home, About Us, Events, and Contact Us.  
Enhancements include:  
- Adding a new **Book Reviews** section  
- Updating the **Events** page with upcoming community events  

Two contributors are simulated:  
- **Morgan** → adds the Book Reviews section  
- **Jamie** → updates the Events page  

## Objectives
- Practice Git branching and collaboration  
- Simulate real-world teamwork with feature branches  
- Document changes clearly in commits and pull requests  

## Tech Stack
- HTML5  
- Git & GitHub  

## Project Structure
.
├── home.html
├── about_us.html
├── events.html
├── contact_us.html
├── book_reviews.html   # Added by Morgan
└── README.md


## Git Workflow
1. **Create main branch** with base files.  
2. **Morgan** works on `book-reviews` branch:  
   - Adds `book_reviews.html`  
   - Commits and pushes changes  
   - Opens PR → merge into main  
3. **Jamie** works on `update-events` branch:  
   - Updates `events.html` with new event details  
   - Commits and pushes changes  
   - Opens PR → merge into main  
4. **Merge Strategy**: Use pull requests to simulate collaboration.  

## Getting Started
1. Clone repo:
   ```bash
   git clone https://github.com/<your-username>/greenwood-library.git
   cd greenwood-library
2. Open HTML files in a browser.
3. Review feature branches (book-reviews, update-events) in GitHub.

Contributors

Morgan → Book Reviews section
git commit -m "Add new Book Reviews page with sample content"
git commit -m "Link Book Reviews page from navigation menu"
git commit -m "Refine Book Reviews layout for readability"

Jamie → Events page updates
git commit -m "Update Events page with upcoming library workshops"
git commit -m "Add community meetup details to Events page"
git commit -m "Improve Events page formatting for clarity"
