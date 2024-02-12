
Link:
https://austinshigh.github.io/ttt2/ttt3.html


Careful planning of the structure of the HTML can assist with
identifying selectors in both CSS and Javascript. How do you think the structure of ttt3
helps or does not help with that goal?

- The 'square' class which I added to the HTML allows me to select all squares using a single 'getElementsByClassName' function.
I could have achieved a similar result via using string interpolation in a 'for' loop to set onClick handlers for each square using `sq${id}`.