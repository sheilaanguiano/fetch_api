# Doggo Select

By using the provided HTML and CSS the objective of the project was to learn how to make network request and handle responses with the Fetch API, instead of the XMLHttpRequest(XHR) to the [Dog API](https://dog.ceo/dog-api/)

### Description:
The projects uses a reusable data fetching function, that:
runs the fetch 
checks the status using a helper function
Parses to JSON
Catches errors

By using this function with the Promises.all() method, we fetch the data that populates the “Select Breed” menu and random photo, with the assistance of their respective helper functions.

Finally, in order to learn how to change the default fetch behavior, the `postData` function, that submits the content of the form to the [JSON Placeholder API](https://jsonplaceholder.typicode.com/), using the comment endpoint.

