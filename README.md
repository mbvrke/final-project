This page is designed to serve as a "to do list" for the user. 

It has two different input fields. One input field takes in a string (a task to add to the To Do List). The other input field takes in # and moves the corresponding task to the completed list.

To save the task list, it stores the different inputs in an array and iterates through them to display each item as its own list item.

To remove tasks from the list, it matches the number the user inputs with the array index. It splices the array and then displays the spliced array value under completed tasks.

Upon reload, the task list will repopulate. The tasks will stay in the To Do column until Reset is pressed. Completed tasks do not reload.
