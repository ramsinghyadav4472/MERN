# MERN Learning Project - Product Display App

A simple full-stack application built while learning the MERN (MongoDB, Express, React, Node.js) stack. This project demonstrates fetching data from an external API and displaying it in a clean, responsive interface.

## 📋 Project Overview

This is a beginner-friendly project that showcases:

- **Backend**: Express.js server with API endpoint
- **Frontend**: Vanilla JavaScript with HTML/CSS
- **API Integration**: Fetching product data from DummyJSON API
- **Static File Serving**: Express serving static frontend files

## 🚀 Features

- Fetches product data from external API (`https://dummyjson.com/products`)
- Displays products in a responsive card layout
- Loading indicator while data is being fetched
- Clean and modern UI design

## 🛠️ Tech Stack

- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **Vanilla JavaScript** - Frontend logic
- **HTML5 & CSS3** - Structure and styling
- **DummyJSON API** - External data source

## 📁 Project Structure

```
frontend-backend-main/
├── public/
│   ├── index.html      # Main HTML file
│   ├── script.js       # Frontend JavaScript
│   └── style.css       # Styling
├── server.js           # Express server
├── package.json        # Dependencies
└── README.md          # Project documentation
```

## 🔧 Installation & Setup

### Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)

### Steps to Run

1. **Clone or download the project**

   ```bash
   cd frontend-backend-main
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the server**

   ```bash
   node server.js
   ```

4. **Open in browser**

   ```
   http://localhost:3000
   ```

## 📝 How It Works

### Backend (`server.js`)

- Creates an Express server
- Serves static files from the `public` folder
- Provides `/api/products` endpoint that fetches data from DummyJSON API
- Runs on port 3000 (or environment variable PORT)

### Frontend

- **`index.html`**: Basic structure with a container for products and a loader
- **`script.js`**: Fetches data from `/api/products` and dynamically creates product cards
- **`style.css`**: Styles the product cards in a responsive grid layout

## 🌐 API Endpoint

**GET** `/api/products`

- Fetches product data from `https://dummyjson.com/products`
- Returns JSON with product information including:
  - Product title
  - Product thumbnail image
  - Additional product details

## 📸 Features Demonstrated

✅ Setting up an Express server  
✅ Serving static files  
✅ Creating API endpoints  
✅ Fetching external API data  
✅ Frontend-backend communication  
✅ Dynamic DOM manipulation  
✅ Responsive CSS grid layout  

## 🎓 Learning Outcomes

This project helped me understand:

- How to set up a basic Express.js server
- Serving static frontend files from a backend
- Making API calls from both frontend and backend
- Handling asynchronous operations with `fetch` and `async/await`
- Creating responsive layouts with CSS Grid
- ES6 modules (`type: "module"` in package.json)

## 🔮 Future Enhancements

- [ ] Add MongoDB database integration
- [ ] Implement CRUD operations
- [ ] Add user authentication
- [ ] Convert frontend to React
- [ ] Add search and filter functionality
- [ ] Implement pagination
- [ ] Add error handling and validation

## 📦 Dependencies

```json
{
  "express": "^4.22.1",
  "node-fetch": "^3.3.2"
}
```

## 📄 License

This is a learning project and is free to use for educational purposes.

## 🤝 Contributing

This is a personal learning project, but suggestions and feedback are always welcome!

---

**Happy Learning! 🚀**
