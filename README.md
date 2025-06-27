📰 NewsNest – A Modern News Aggregator Web App
NewsNest is a dynamic and responsive news aggregator web application built during my internship at BrainlyHood Technologies. It fetches and displays real-time news articles across multiple categories using a third-party news API.

🚀 Tech Stack

Frontend:
React.js (Component-based architecture)
HTML5, CSS3, JavaScript
Bootstrap (for responsive UI)

Backend:
Node.js (used for server interaction / future extensibility)
Other Tools:
React Router (for navigation)
News API (for fetching real-time data)

🔄 Workflow & Features
Navbar (Component)
A responsive navigation bar (NavBar.js) with a hamburger toggle on smaller screens. It allows users to filter news by category like:

Business
Entertainment
Health
Science
Sports
Technology
News Feed (Dynamic Cards)

Each article is represented as a card (NewsItem.js) with:
Title, description, image
Author, published date
Source badge (category-specific colored badge)
External link to full article
Loading Spinner (UX Enhancement)
Displays a loading GIF (Spinner.js) while data is being fetched, ensuring a smooth user experience
Pagination / Infinite Scroll (Optional)
The app supports pagination or infinite scroll to browse more articles (if implemented).

🔧 How to Run Locally
bash
Copy
Edit
# Clone the repository
git clone https://github.com/your-username/newsnest.git
cd newsnest

# Install dependencies
npm install

# Start the app
npm start
Make sure to replace your-username with your GitHub username, and add your API key in a .env file if required.

🌟 Highlights
Built in a real-world internship environment

Clean and modular component structure

Responsive layout using Bootstrap

Real-time news data rendered dynamically

