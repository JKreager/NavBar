A Single Page Application (SPA) which toggles the links to show or hide, and links to the page within the single page, underneath the bar. 
React
Bootstrap 5.0.0-alpha1


Navigation Bar: The Bootstrap navigation bar contains links trigger route changes.

React Component: Manages the routing of the SPA

Content Loading: Content is loaded asynchronously using the fetch API, and the loaded HTML is displayed on the designated element with the ID info.

Routing: The useEffect hook listens for hash changes (hashchange event) and triggers the router function, which updates the content based on the current route.

This project is licensed under the MIT License.
