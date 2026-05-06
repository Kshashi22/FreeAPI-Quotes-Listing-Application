# ❝ Quote Gallery 

A clean, paginated quotes listing app built with **React + TypeScript + Vite**, powered by the [FreeAPI.app](https://freeapi.app) public quotes endpoint.

<img width="1218" height="565" alt="Screenshot (263)" src="https://github.com/user-attachments/assets/4b30e624-7aab-4060-9829-4ee0266c58a2" />


## Features

- Fetches quotes from the FreeAPI public quotes API
- Displays quotes in a responsive card grid (12 per page)
- Pagination — navigate through all available quotes
- Dark, elegant UI with smooth hover animations
- Loading spinner & error state handling

## Tech Stack

- React 19 + TypeScript
- Vite
- Pure CSS (no external UI library)

## API

```
GET https://api.freeapi.app/api/v1/public/quotes?page=1&limit=12
```

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Build

```bash
npm run build
```
