# Blood-Responsive-APP
Creating web application using HTML, CSS, and JavaScript is a great way to help users find blood donors and request blood when needed.
## HTML Structure:
The HTML structure defines the basic layout and content of the web application. It consists of a header, a main content area, and a footer.
In the header, there's a welcoming message to users.
The main content area is divided into two sections: "Available Donors" and "Request Blood."
The "Available Donors" section displays a list of available blood donors, which will be populated dynamically using JavaScript.
The "Request Blood" section contains a form where users can request blood by selecting the blood type and specifying the number of units they need.
## CSS Styles (styles.css):
The CSS file provides styles and layout for the HTML elements, making the application visually appealing and responsive.
It sets styles for headers, sections, lists, forms, and buttons to create a consistent and user-friendly interface.
The styles ensure that the application looks good on both desktop and mobile devices.
## JavaScript (script.js):
The JavaScript code adds functionality to the web application.
It starts by defining sample donor data (you would typically retrieve this data from a database or an API in a real application).
It then populates the "Available Donors" list dynamically by creating list items for each donor using the donor data.
The script also handles the blood request form submission. When the user submits the form, it prevents the default form submission behavior and retrieves the selected blood type and the number of units requested.
The JavaScript can include logic to send the request to a server or perform any necessary validation. In this example, it shows an alert confirming the request submission.
