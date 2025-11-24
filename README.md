<h2>🌟 Features</h2>

Add Employee form

Employee list with edit/delete

Search employees

Auto reload after add/update/delete

Axios API integration

Responsive UI


<h2>Tech Stack</h2>

React.js (Vite)

Axios

CSS

<h3> Run Frontend Locally</h3>
Install packages
npm install

Start dev server
npm run dev


Runs at:
👉 http://localhost:5173

🔗 API Configuration

In config.js:

export const API_URL = import.meta.env.VITE_API_URL || "http://localhost:5000";


Use like:

axios.get(`${API_URL}/api/employees`)
