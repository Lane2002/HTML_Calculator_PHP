# HTML_Calculator_PHP
LEARN PHP
HTML - PHP Calculator
Apply your understanding of handling HTML forms in PHP to create a calculator.

Tasks
9/9 Complete
Mark the tasks as complete by checking them off
Front-end Forms
1.
You are going to build a calculator to do addition and division of two integer numbers.

Each calculator will appear as a separate form for the user on the initial page, which will be contained in index.php.

Begin by creating the two forms. Give each one a heading stating what the calculator will do. Be sure to include two number inputs for each form and a submit button.

Don’t worry about giving the inputs names or the form actions in this step.


Stuck? Get a hint
2.
Each form needs to be submitted to its own file on the back-end so that the correct math gets performed with the two numbers.

We’ve already created addition.php and division.php for you.

Update your forms so that each one gets submitted to the correct back-end file.


Stuck? Get a hint
3.
We need to decide which method to use for our forms. Since we’d like to be able to share our calculations with friends via URL, let’s use GET as the form method.

Set this on both forms.


Stuck? Get a hint
4.
To enable processing the inputs with PHP, give each input a unique name.


Stuck? Get a hint
Back-end Processing
5.
At this point, you may want to print the contents of the appropriate superglobal within both addition.php and division.php to make sure that your data is making it to the backend.

If it is not, make sure that each form action is set to the corresponding file and that the inputs have names.


Stuck? Get a hint
6.
Now, try printing just the correct result within addition.php.


Stuck? Get a hint
7.
Update addition.php to have a more helpful message including what numbers were added.

You can play around with the styling to get it how you like it.


Stuck? Get a hint
8.
Now, implement the back-end processing for division.php.


Stuck? Get a hint
Above and Beyond
9.
If you would like more of a challenge, you could:

Implement more complicated math operations, like the Pythagorean theorem. The calculator could return the length of a hypotenuse given the two other sides.
Add more CSS styling to the application.
Combine the two forms into a single form. To submit the forms to the correct file, use the formaction attribute
