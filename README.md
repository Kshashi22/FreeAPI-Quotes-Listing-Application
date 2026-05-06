
# FreeAPI Quotes Listing Application

A simple web application that fetches and displays quotes from a free public API. This project demonstrates how to integrate APIs, handle asynchronous data, and dynamically render content on a web page.

---

## Features

* Fetch quotes from a free public API
* Display quotes dynamically on the UI
* Show author names along with quotes
* Refresh or load new quotes
* Simple and responsive user interface
* Lightweight and fast

---

## Tech Stack

* Frontend: HTML, CSS, JavaScript
* API: Free public quotes API (e.g., Quotable API)
* Tools: VS Code, Git, Browser DevTools

---

## Project Structure

```
FreeAPI-Quotes-Listing-Application/
│── index.html
│── style.css
│── script.js
│── README.md
```

---

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/FreeAPI-Quotes-Listing-Application.git
   ```

2. Navigate to the project directory:

   ```bash
   cd FreeAPI-Quotes-Listing-Application
   ```

3. Open the `index.html` file in your browser

---

## API Integration

Example API used:

```
https://api.quotable.io/quotes
```

### Fetch Example

```javascript
fetch('https://api.quotable.io/quotes')
  .then(response => response.json())
  .then(data => console.log(data));
```

---

## How It Works

1. The application sends a request to the quotes API
2. The API returns data in JSON format
3. The application processes the data
4. Quotes and authors are displayed dynamically on the webpage

---

## Future Improvements

* Add category-based filtering
* Search quotes by keyword or author
* Add pagination or infinite scrolling
* Save favorite quotes locally
* Improve UI/UX with animations

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a pull request


## Acknowledgements

* Public APIs providing free quote data
* Open-source development community

