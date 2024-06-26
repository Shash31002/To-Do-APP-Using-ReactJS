# To-Do-APP-Using-ReactJS
This To-D0 APP can add new tasks and also delete the tasks by clicking on them.
This is a simple React application that creates a dynamic “TODO list” where users can add, edit, and delete items. Let’s break it down:

Import Statements:
The code begins by importing necessary components from React and Bootstrap.
Components imported include Component, Container, Row, Col, Button, InputGroup, FormControl, and ListGroup.

Class Component:
The App class extends Component, which is a base class for React components.
The constructor initializes the component’s state with an empty userInput and an empty array for the list.

Methods:
updateInput(value): Updates the userInput state when the user types into the input field.
addItem(): Adds an item to the list if the user input is not empty.
deleteItem(key): Removes an item from the list based on its unique id.
editItem(index): Allows the user to edit an existing item in the list.

Render Method:
The render() method returns JSX (React elements) that define the UI.
It includes a title (“TODO LIST”), an input field, and a button to add items.
The list of items is displayed using the map() function.

Bootstrap Styling:
Bootstrap classes are used to style the UI components (e.g., mb-3, mt-2, etc.).
Overall, this code creates a basic TODO list application with React and Bootstrap. Users can add items, edit existing items, and delete items from the list.

Importing React App modlues from create-React-App:

Credits: 

https://github.com/facebook/create-react-app

https://www.geeksforgeeks.org/create-todo-app-using-reactjs/
