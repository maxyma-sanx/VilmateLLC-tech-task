# VilmateLLC-tech-task

## Dynamic Divs Manipulation

This is a simple HTML and JavaScript project that dynamically adds 100 div elements to the body of an HTML page. Each div contains unique text and is initially centered both horizontally and vertically. The user can click on any div element to move it to the top of the page, and clicking on it again will return it to its original position.

## Instructions

- Clone or download this repository to your local machine.
- Open the index.html file in your web browser.
- You will see 100 div elements with unique text displayed on the page.
- Click on any div element to move it to the top of the page.
- Click on the same div element again to return it to its original position.
- You can click on div elements in any sequence; it doesn't have to be consecutive.
- The code is implemented using plain JavaScript without any external libraries or frameworks.
- This project is designed to work on both desktop and mobile browsers.

## Implementation Details

- The div elements are created and added to the body of the HTML document dynamically using JavaScript.
- Each div has a unique identifier (e.g., div1, div2, div3, etc.) and is styled to be centered both horizontally and vertically using CSS.
- JavaScript event listeners are used to handle the click events on the div elements.
- When a div is clicked, it is moved to the top of the body using the appendChild method, effectively making it the first child of the body element.
- Clicking on the same div again will return it to its original position using the same method.

Enjoy experimenting with the dynamic manipulation of div elements!
