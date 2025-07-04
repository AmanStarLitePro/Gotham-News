# 🗞️ Gotham News - React JS News Web App

Gotham News is a dynamic and responsive React-based web application that delivers real-time news to users using the [NewsAPI](https://newsapi.org/). It features a sleek Bootstrap-based design and utilizes React concepts like props, states, and routing to provide a seamless user experience.

---

## 🚀 Features

- 🔍 Fetches live news data using `NewsAPI`
- 🧭 Category-based news filtering (e.g., Business, Sports, Health, Entertainment)
- ⚡ Responsive and mobile-friendly Bootstrap UI
- 🔁 Dynamic content updates via `useState` and `useEffect`
- 🌐 Routing handled with `React Router DOM`
- 📸 Thumbnail preview for each news article
- 🕒 Displays published date, author, and news source
- 🧼 Clean and minimal card-based layout

---

## 🛠️ Tech Stack

| Tech            | Description                            |
|-----------------|----------------------------------------|
| React JS        | Frontend framework                     |
| NewsAPI         | Fetches real-time news data            |
| Bootstrap       | Styling and responsive design          |
| React Router    | Handles multiple routes and navigation |
| JSX + CSS       | Component-based structure and design   |

---

## 📸 Screenshots

| Home Page                             | News Cards                           |
|--------------------------------------|--------------------------------------|
| ![Home Page](./screenshots/home.png) | ![News Card](./screenshots/card.png) |

---

## 📂 Folder Structure

```

Gotham-News/
├── public/
├── src/
│   ├── components/
│   │   └── NewsItem.js
│   ├── App.js
│   ├── News.js
│   ├── index.js
│   └── ...
├── .env
├── package.json
└── README.md

````

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/AmanStarLitePro/Gotham-News.git
cd Gotham-News
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root directory and add your NewsAPI key:

```env
REACT_APP_NEWS_API=your_news_api_key_here
```

Get your API key from [https://newsapi.org](https://newsapi.org).

### 4. Run the App

```bash
npm start
```

The app will run at `http://localhost:3000`.

---

## 📌 To-Do / Future Enhancements

* Add dark mode support 🌙
* Pagination for longer article lists
* Bookmark/save articles
* Search functionality 🔍
* Language selection / Region-based filtering

## 👨‍💻 Author

**Aman Kumar**
📧 [amanstarlitepro@gmail.com](mailto:amanstarlitepro@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/aman-kumar-a487b5252/)
🌐 [GitHub](https://github.com/AmanStarLitePro)

---

> “Stay updated with Gotham News – your daily dose of headlines, all in one place.”

