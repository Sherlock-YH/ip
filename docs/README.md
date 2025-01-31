# User Guide

## Features 

### List

User can explore all the tasks recorded

### Add ToDo Tasks

User can add ToDo task by entering: todo <task description>

### Add Deadline Tasks

User can add Deadline by entering: deadline <task description> /by <deadline DD-MM-YYYY>

### Add Event Tasks

User can add Event by entering: event <task description> /from <start date> /to <end date>

### Mark finished Tasks

User can mark a task to indicate it is finished/completed by entering: mark <task number>

### Unmark Tasks

User can undo their mark of finished tasks if the task is not done by entering: unmark <task number>

### Delete Tasks

User can delete tasks by entering: delete <task number> OR delete all  

### Find task

User can find task regarding the descriptions of tasks by entering: find <task description>

### Storage

The tasks will be stored and read every time when the user start and end Duke

## Usage 
```
Note that all commands are case-sensitive
```

### `list` - list down all the tasks

Example of usage: 

`list`

Expected outcome:

showing all tasks and give the number of tasks

```
1.[T][ ] meeting 
2.[D][ ] HW  (by: 2 Mar 2023)
3.[E][ ] Dinner (from:  7  to:  9pm)

Found 3 Task!
============================================================
```

### `todo` - add todo task

Example of usage:

`todo meeting`

Expected outcome:

A todo task is added

```
Added: todo meeting 
============================================================
```

### `deadline` - add deadline task

Example of usage:

`deadline HW /by 02/03/2023`

Expected outcome:

A deadline task is added

```
Added: deadline HW /by 02/03/2023
============================================================
```

### `event` - add event task

Example of usage:

`event Dinner /from 7 /to 9pm`

Expected outcome:

An event task is added

```
Added: event Dinner /from 7 /to 9pm
============================================================
```

### `mark` - mark finished task

Example of usage:

`mark 1`

Expected outcome:

task 1 is marked as done

```
Nice! You have done Task 1
============================================================
```

### `unmark` - unmark task

Example of usage:

`unmark 1`

Expected outcome:

task 1 is marked as not done

```
Okay, I have unmarked Task 1
============================================================
```

### `delete` - delete task

Example of usage:

`delete 1`

Expected outcome:

task 1 is deleted

```
Task 1 deleted
============================================================
```

### `find` - find tasks

Example of usage:

`find Dinner`

Expected outcome:

matched tasks will be listed down

```
Found 1 Task!
Here are the matching tasks in your list:
1.[E][ ] Dinner (from:  7  to:  9pm)
============================================================
```

### `bye` - end program

Example of usage:

`bye`

Expected outcome:

program ended and show farewell message

tasks are stored in .txt file

```
Bye! See you next time!
============================================================
```

### `help` - show all commands

Example of usage:

`help`

Expected outcome:

show commands and the way that user should enter

```
If you wish to view all tasks -Enter: 

list
------------------------------------------------------------
If you wish to add a ToDo task -Enter: 

todo <task description>
------------------------------------------------------------
If you wish to add a Deadline task -Enter: 

deadline <task description> /by <deadline date DD/MM/YYYY>
------------------------------------------------------------
If you wish to add a Event task -Enter: 

event <task description> /from <start date> /to <end date> 
------------------------------------------------------------
If you wish to mark a task as Done -Enter: 

mark <task number>
------------------------------------------------------------
If you wish to undo a mark -Enter: 

unmark <task number>
------------------------------------------------------------
If you wish to delete a task -Enter: 

delete <task number>
OR delete all (delete all tasks)
------------------------------------------------------------
If you wish to find tasks -Enter: 

find <task description>
------------------------------------------------------------
If you wish to exit the program -Enter: 

bye
============================================================
```