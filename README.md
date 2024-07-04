 Name:Rushali Behura
 
 Company:CODTECH IT SOLUTIONS
 
 ID:CT08DS2035
 
 Domain-Web development 
 
 Duration-june-july 2024
 
 Mentor-Savani Gouni





 
Overview of task-1


Html code- Purpose: The code is for a simple To-Do List application. Structure: • The HTML document has a head section that contains metadata about the document. • The body section contains the content of the application, which is wrapped in a div element with the class "container". • The application has three main components:
1.	A heading (h1) that displays the title "To-Do List".
2.	A input field (input) to enter new tasks, along with an "Add Task" button (button).
3.	An unordered list (ul) to display the tasks.
4.	Key Elements:
5.	 • input element with id "new-task-input" for entering new tasks.
6.	  • button element with id "add-task-button" to add new tasks to the list.
7.	   • ul element with id "task-list" to display the list of tasks.
8.• script tag that links to an external JavaScript file (script.js) that will contain the logic for the application. 
• link tag that links to an external stylesheet (style.css) for styling the application.

CSS code-

Here's a simple overview of the CSS code: Body
• Sets the font family to Arial, sans-serif
• Sets the background color to a blue-ish color (#768eec)
• Centers the content both horizontally and vertically using flexbox
 • Sets the height to 100vh (full screen height) and removes margins Container
• Sets the background color to a reddish-pink color (#e67a7a)
• Adds padding, border radius, and a box shadow to create a card-like effect
• Sets the width to 300px and centers the text Headings (h1)
• Adds a margin bottom of 20px to create space between the heading and other elements Input fields
• Sets the width to 100% minus 22px (to account for padding and borders)
 • Adds padding, border, and border radius to create a styled input field
 • Sets the margin bottom to 10px to create space between input fields Buttons
 • Sets the padding, border, background color, and text color to create a styled button
• Sets the cursor to a pointer on hover
 • Sets the width to 100% to make the button full-width
• Defines a hover state with a darker green background color Lists (ul and li)
• Removes the default list style and padding
• Sets the background color, padding, margin, and border radius to create a styled list item
 • Uses flexbox to center the content and create space between list items
• Defines a button style within list items with a red background color and hover state Overall, this CSS code is styling a simple web page with a centered container, input fields, buttons, and a list of items. The design is clean and modern, with a focus on creating a visually appealing user interface.

JavaScript code-

 Here's a simple overview of the JavaScript code: Variables and Event Listeners
 • The code gets references to two HTML elements: taskInput (an input field with the id "new-task-input") and addTaskButton (a button with the id "add-task-button").
 • An event listener is added to the addTaskButton to listen for clicks. Click Event Handler
 • When the addTaskButton is clicked, the event handler function is executed.
 • The function gets the value of the taskInput field, trims any whitespace, and stores it in the taskText variable. • If taskText is not an empty string, the function creates a new list item (li) and a delete button (button).
 • The list item's text content is set to taskText, and the delete button's text content is set to "Delete".
 • The delete button is added to the list item, and an event listener is added to the delete button to remove the list item when clicked.
 • The list item is then added to the task list (taskList) element. • Finally, the taskInput field is cleared by setting its value to an empty string. In summary, this JavaScript code is responsible for:
1.	Getting references to the input field and add task button.
2.	Adding an event listener to the add task button.
3.	When the button is clicked, creating a new list item with the input field's value and a delete button.
4.	Adding the list item to the task list and clearing the input field. This code is likely part of a to-do list app, where users can add new tasks by typing in the input field and clicking the add task button. The tasks are then displayed in a list, and each task has a delete button to remove it from the list.

# CODTECH-TASK-1
