# Mini Posts App

A simple and responsive JavaScript web application that fetches posts from an API and displays them as cards. This project was built as part of my Week 2 JavaScript practice.

## Features

- Fetch posts from a public REST API
- Display post titles and descriptions
- Show the User ID for each post
- Loading, success, and error messages
- Handle API and network errors using `try...catch`
- Render post cards dynamically using JavaScript DOM methods
- Responsive layout for different screen sizes

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JavaScript)
- Fetch API
- JSONPlaceholder API

## API Used

This project uses the JSONPlaceholder Posts API:

https://jsonplaceholder.typicode.com/posts

The API provides sample post data, including post IDs, user IDs, titles, and bodies.

## Project Structure

```text
mini-posts-app/
├── index.html
├── style.css
├── script.js
└── README.md
```

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in your browser, or use the Live Server extension.
4. Click the **Load Posts** button.
5. Wait for the posts to load and appear on the page.

An internet connection is required to fetch posts from the API.

## What I Learned

- Selecting HTML elements using `document.querySelector()`
- Handling button clicks with `addEventListener()`
- Using `fetch()` to request API data
- Working with `async` and `await`
- Converting API responses into JSON using `response.json()`
- Iterating through arrays with `forEach()`
- Creating HTML elements dynamically using `document.createElement()`
- Updating content with `textContent`
- Adding elements to the page using `append()`
- Handling errors with `try...catch`
- Displaying loading, success, and error states

## Future Improvements

- Add a search feature for posts
- Add pagination or a Load More button
- Filter posts by User ID
- Add a post details view
- Improve accessibility and UI interactions

## Author

**Muhammad Bin Abdul Mannan**

## License

This project is created for learning and practice purposes.
