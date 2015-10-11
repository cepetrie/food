Requirements: Build a form that uses form validation to allow/require a user to select from each of the following courses, by turn:

1) Appetizer: Require your user to select 1, but no more than 2 appetizers (minimum 3 selections per category)

2) Main course: Require your user to select only 1 main course (minimum 2 selections per category)

3) Sides: Require your user to select 1-3 side dishes (minimum 3 selections per category)

4) Beverage: Require your user to select 1 beverage (minimum 2 selections per category)

5) Dessert: Require your user to select 1 dessert (minimum 2 selections per category)

Categories: Besides allowing the user to make the selections above, the user must be presented with 2 categories for each item.  For example, for Appetizer, you could allow the user to select either the Potterverse and TrekFest.  Since appetizers requires 3 selections per category, you would need 6 selections total, of which only 3 will ever be visible at one time.

Show/Hide or Slide Down: Each of the selections made (appetizer, main course, etc.) must only show once a category is chosen.  If another category is chosen, the previous category must hide again.  Only one category per course can be shown at a time!

Form items cleared: On hide, the form elements must clear from the un-chosen category.  This is so the form doesn't submit form data twice.

Form Submission: In order to test how the form works, please use the following formhandler upon correct submission:

<form action="http://www.newmanic.com/formtest.asp" method="post">

Once all data is validated, the above can be used to double check to be sure no incorrect info was submitted.
