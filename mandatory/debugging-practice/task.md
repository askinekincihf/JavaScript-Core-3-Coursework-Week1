# My Book Library

My website should be able to:

- View a list of books that I've read
- Add books to a list of books that I've read
  - Including title, author, number of pages and if I've read it
  - If any of the information is missing it shouldn't add the book and should show an alert
- Remove books from my list

## Bugs to be fixed

1. Website loads but nothing works in my javascript
  - Syntax Error in line 57 - added missing parenthesis.
2. Website loads but nothing happens
  - Reference Error in line 93 - delBut is not defined - corrected all related names as delButton.
3. Error in console when you try to add a book
  - Reference Error in line 41 - library is not defined - corrected the name of the variable as myLibrary.
4. It uses the title name as the author name
  - Logical Error in line 40 - fixed as let book = new Book(title.value, author.value, pages.value, check.checked); 
5. Delete button is broken
  - Reference Error in line 97 - deleted "s" at the end of click.
6. When I add a book that I say I've read - it saves the wrong answer
  - Logical Error in line 79 - fixed if condition.

I think there are other some other small bugs in my code...but I'm lazy so I can't fix them all.

I wish somebody would help me!
