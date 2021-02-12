My website consists of a registration page that will serve as the initial landing page. There is a form consisting of name, email, gender(dropdown),
and date of birth. The user is not allowed to submit and move on until all 4 input fields have been filled out, otherwise the user will be notified. 
Additionially, I used regex in the email field to verify that the user indeed put in a valid email address that includes an '@' and a '.'
The bottom of my registration page is a simple html table that lists the prices and subscription options for the website.

After the form has been submitted, the user is taken to the main page which consists of movie titles and posters that were populated by querying The
Movie Database (TMDB). By hovering over each movie, the user will get to see a brief description of the film. The header of this page consists of 
a search bar and a logout button, which takes the user back to registration. The search bar allows the user to search for films he or she would like
to see, and after pressing enter a query is sent to TMDB to repopulate the main page only with movies that contain the string in the search bar.
The search bar is then cleared.

For this assignment I used pure html, css, and javascript. To utilize TMDB, I signed up on their website and retrieved an API key.