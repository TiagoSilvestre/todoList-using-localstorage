# TodoList using javascript and localstorage
This is a todo list in javascript that uses localstorage to save the list data. 
It only requires a browser to use it.


I'm designing interfaces to be easy to change the data storage, for example save it in a database.

The `getList()` function return the list of objects, in this case from localstorage, like this

[
    {name: 'Activity', order: '5'},
    {name: 'Walk', order: '2'},
    {name: 'Run', order: '3'},
    {name: 'Dance', order: '1'},
]

You can transform the list, use the `setList()` method to save the list.