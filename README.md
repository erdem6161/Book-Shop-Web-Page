# Libraries

1- json-server
2- axios
4- react-router-dom
3- react-toastify

Stage 1
-------------
- React Router DOM structure will be used for page navigation.
- We updated the base URL with axios to http://localhost:3005.
- We fetched data from the API accessed with JSON server using the function defined with axios.
- A "addbook" page was created to add products.
- A form structure will be created.
- Values to be written in the form's inputs will be tracked with useState, and onChange structure will follow the values.
- The information from the form will be stored in an object and sent to the JSON server using axios.

Stage 2
--------
- Redirect to the edit page when the edit icon is clicked.
- The information of the product clicked for the edit icon will be sent to the edit page.
- To find the product based on its ID, we will use the useParams structure to search among all the products called with axios using the find function.
- Values to be assigned to inputs will be found.
- The found values can be updated.
- After the update process, we will return to the "booklist" page with the react-toastify structure.
