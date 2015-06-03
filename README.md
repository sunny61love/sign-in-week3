# Signin Screen

## Complete these steps to create a signin prototype:

1. When the user presses the .signin button, fade in the modal window
2. When the user presses the .close button, fade out the modal window
3. When a user hits .submit, check both fields to see if their .val() is blank (consider what a blank response might looks like) highlight the appropriate input field by adding the .error class to it, then shake the whole form (simply use .animate(), or try using CSS @keyframes) so it notifies the user that something has gone wrong
4. When the user enters something for both fields, hide the .modal, .signin and .hello 
5. (Bonus) Allow the user to click the .modal to close itself
  - tricky, consider what happens when two elements that are overlapping are both waiting for a click

## Things to consider: 

- How do you select a CSS element by "name" attribute?
- Be sure not to trigger the shake animation for each field, just once for both
- Can you create the animation using just CSS? (you don't have to do it, just consider how)
- Is there a better way to get a more "linear" shake animation?
- What if the user hits submit a bunch of times - what happens to the animation?
- Remove the .error message once a field gets edited/rectified
- If both input elements have the same functionality, can they share code?

What else could you add? Consider you may want to check the input fields for errors (blank value) as soon as you put your mouse in or out (Think UX!)
