# helpdesk-help-center
Digital Marketing Help Center

A simple, searchable help-center web page with 10 FAQ answers for common support issues in Google Ads, conversion tracking, Excel reports and landing pages. Built as a practice project for a Backoffice Helpdesk role.

Live demo: https://sushant12shahdeo.github.io/helpdesk-help-center/file:///C:/Users/Admin/Downloads/index.html

Features
10 FAQs grouped by category: Google Ads, Tracking, Excel, Web/HTML
Search box that filters articles as you type
Expandable answers with numbered fix steps
"Escalate if" notes that show when an issue should go to a specialist team
Responsive layout that works on phone and desktop
"No results" message and a "Still need help?" contact section
Built with
HTML5
CSS3
Bootstrap 5 (loaded from a CDN)
JavaScript (basic search filter)
Project structure
helpdesk-help-center/
├── index.html    # the whole page: HTML, CSS and JavaScript
└── README.md
How to run locally
Download or clone this repository.
Open index.html in any web browser.
Type a keyword such as ad, #N/A or conversions in the search box.

An internet connection is needed because Bootstrap loads from a CDN.

How the search works

Each FAQ item stores its keywords in a data-text attribute. When you type, a small JavaScript function compares your text with each item's keywords and content, and hides the items that do not match.

What this project shows
Writing clear, step-by-step support documentation
Building a self-service knowledge base to reduce repeat queries
Basic HTML, CSS, Bootstrap and JavaScript
Knowing when to escalate an issue instead of guessing
Notes

This is a practice project. The FAQ content is based on sample support scenarios, and the contact email is a placeholder.

Author

Lal Sushant Nath Shahdeo

LinkedIn: https://linkedin.com/in/sushant-shahdeo
GitHub: https://github.com/sushant12shahdeo
