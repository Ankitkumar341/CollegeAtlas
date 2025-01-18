# CollegeAtlas

CollegeAtlas is a simple web application that allows users to search for colleges by name. The application fetches data from the [Hipolabs Universities API](http://universities.hipolabs.com/search?name=) and displays the results in a list.

## Project Structure

- `index.html`: The main HTML file that contains the structure of the web page.
- `style.css`: The CSS file that contains the styles for the web page.
- `app.js`: The JavaScript file that contains the logic for fetching and displaying the college data.

## How It Works

1. **HTML Structure**:
    - The `index.html` file contains an input field for the search query and a button to trigger the search.
    - It also includes an unordered list (`<ul>`) to display the search results.

2. **CSS Styling**:
    - The `style.css` file styles the input field, button, and list to make the application look attractive and professional.
    - It includes responsive design to ensure the application works well on mobile devices.

3. **JavaScript Logic**:
    - The `app.js` file contains the logic for fetching and displaying the college data.
    - When the user clicks the search button, the `getColleges` function is called with the search query.
    - The `getColleges` function makes an HTTP GET request to the Hipolabs Universities API using Axios.
    - The response data is then passed to the `show` function, which creates list items for each college and appends them to the unordered list.


## How to Run

1. Open `index.html` in a web browser.
2. Enter the name of a college in the search bar.
3. Click the "Search" button to fetch and display the list of colleges.

## Screenshots
![alt text](<Screenshot 2025-01-18 152840.png>)
![alt text](<Screenshot (101)-1.png>)
## Dependencies

- [Axios](https://cdn.jsdelivr.net/npm/axios@1.6.7/dist/axios.min.js): A promise-based HTTP client for the browser.
