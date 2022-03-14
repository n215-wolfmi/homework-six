# Homework Six

Author: Matthew Wolf, IUPUI, Spring 2022

Web 4 Link to homework assignment:
https://in-info-web4.informatics.iupui.edu/~wolfmi/homework-six/ 


This assignment was to create the tours page and the associated tours pages for each country in the design document. This assignment primarily dealt with mixins and implimenting them into various parts of the project in order to reuse code efficiently in css. Essentailly they are functions that, in this case, store CSS code and when called they bring that code to wherever they are called. You can also pass parameters through a mixin like a JavaScript function to change the base set of code in the circumstance that you are calling the mixin in. This assignment came out alright but I did have a thought that it could be more efficient. For example, for each div that had a separate image I called the mixin for that layout and passed in the correct image link for each separate div. This ultimately cut down a lot of code reuse but I still felt that there could be a better way than targeting each separate div element that requires a different picutre in a layout. Overall, mixins are VERY usefula and valuable for code reuse.
