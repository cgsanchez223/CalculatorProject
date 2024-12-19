This is my entry for unit 11.1 Unit Testing for the Software Engeneering Bootcamp at Stony Brook University
- Made using HTML, CSS, JavaScript, and Jasmine testing.
-------------------------------------------------------------
The purpose of this unit was to learn about Jasmine testing for HTML, CSS, and JavaScript.

- We are given a Calculator project that calculates the yearly rate of a loan depending on the amount and the term.
- After writing the code, we had to write test.js files in order to run our code.
- A Jasmine test html file is created linking the projects as well as necessary code taken from (https://jasmine.github.io/)
- In order to properly run Jasmine files, the following need to be linked in the test html file:
-------------------------------------------------------------
<script 
  src="https://unpkg.com/jasmine-core@4.1.0/lib/jasmine-core/jasmine.js"></script>
<script 
  src="https://unpkg.com/jasmine-core@4.1.0/lib/jasmine-core/jasmine-html.js"></script>
<script 
  src="https://unpkg.com/jasmine-core@4.1.0/lib/jasmine-core/boot0.js"></script>
<script 
  src="https://unpkg.com/jasmine-core@4.1.0/lib/jasmine-core/boot1.js"></script>

-------------------------------------------------------------
- In Jasmine, we input relevant information pertaining to the code we write, and then ask it what we are trying to do. ex: it('should calculate the monthly rate correctly') , following by a function with all of the necessary information
- Opening the HTML file for the test will reveal the results of the test for the code.
- If everything if green, everything has worked.

-------------------------------------------------------------
- In order to run, downloaded JavaScript and Jasmine.