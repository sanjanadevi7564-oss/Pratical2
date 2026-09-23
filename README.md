DOCTYPE html>
Ahtml lang"en'V
chead>
<meta charset="UTF-8">
citle>Simple To-Do List</itle>
</head>
<body>
chl>Simple To-Do List</h1>
<?pbp
l/ Step 2: Start the session to store tasks session starto:
I/ Step 3: Initialize the to-do list array if not already set
if (lisset(S_SESSION/'todo_list])1S SESSION'todo_list]=(0;
Il Step 4: Handle form submissions
if (S SERVERI'REQUEST_METHOD] == POST)/
Il Add a new task
if (lempty(S_POST[new_task))1
$_SESSION'todo_list'I0 =$_POST'new_task]:
l/ Step 5: Display the current to-do listQUTPUT
localhost/list2.phr
Simple To-Do List
• enter mark list
 enter student namelist
 enter student namelist
Add a New Task
Enter new task
Add Task
