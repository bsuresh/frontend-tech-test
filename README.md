# frontend-tech-test
Frontend Tech test - The goal of this test is to take some JSON data, manipulate it and present it in a table format. 
Further details can be found in the [Tech Test](./docs/TechTest.md) document.

## Background
This test built upon the below approach and assumptions.

1. The test is to be completed around 40minutes, so the focus is on the functionality and not the design.
2. The test follows KISS principle
3. Test uses VanillaJS without any libraries or frameworks for ease of use and understanding.
4. This test is built to work on modern browsers with one version down refer browserlist file for info.
5. Test will use following API's for speed/progressive enhancement
   - ES6 for modern JS features will be used
   - JS FetchAPI for fetching data from the API
   - JS Promise for handling async operations
   - JS async/await for handling async operations
   - JS Array.prototype.map(), Array.prototype.sort() for looping/sorting the data
   - Intl.Collator for sorting the data in a locale-aware manner (i.e numerical, string, etc)
   - toLocaleString for formatting the currency values
   - CSS (will use reset.css for normalizing the styles)
6. Test will be built using standard HTML file with CSS in the head and JS in the body for speed, ease of use and understanding.
7. Eslint + prettier + editorconfig (dotfiles) will be used for code quality and formatting using IDE plugins.
9. For speed and to focus on functionality, the table will be made scrollable for small screens and mobile devices.
10. Basic error handling will be added for API failures and data formatting issues as a good coding practice.
11. Considering it's a test we are safe to assume that we are going to ignore any CSP, CORS, XSS, etc., security issues.

## Getting Started
Please open into the `index.html` file in the browser to view this test.

- CSS can be found in the head of the `index.html` file.
- JS can be found in the body of the `index.html` file.