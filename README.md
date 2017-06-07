# tasks
Tools and Language I used:
	
  1. CODEIGNITER 3.0 (PHP FRAMEWORK) MVC pattern.
	2. Xampp as local server.
	3. MySQL Database named as "tasks.sql".
	4. For front end I simply used Twitter Bootstrap template.

How it works:
	
  1. As I used Xampp my local link was "http://localhost/tasks" without quotes.
	2. The first page(homepage.php) will ask for user login. Default "username: tasks and password: tasks".
	3. After successful login a page(alltasks.php) will appear with all saved tasks. If there is no tasks only headers will be 	            shown.
	4. In every row of tasks there will be an edit and a delete icon. 
	5. Clicking in edit icon it will refer to a new page to edit that task and update it.
	6. Clicking in delete icon will simply delete that task.
	7. On the nav there is ADD TASK which will redirect to a new page having a form. User will complete that form and add the task.
	8. For ADD and UPDATE, dateCreated and dateUpdated will be automatically saved, so no user input required.
	9. If user is already logged in then "http://localhost/tasks" will be redirected to "alltasks" page.
