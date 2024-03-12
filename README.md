# task-manager
 Web App Class

To ensure immutability when updating the tasks in my React state, I used the spread syntax and map function. When adding a new task, I spread the existing tasks into a new array before adding the new task, preventing direct modification of the original state. Similarly, to toggle the completion status, I mapped over the tasks to create a new array, where I updated the completion status of the task with the matching id. This approach avoids altering the original tasks array directly while keeping the state updates pure and predictable.





