### Udemy Course "React the Complete Guide" Exercise 2: setState exercise

You can enter text in the input field.

If the text length is less than 5, you'll see "Text too short" below the input field. If the text length is equal to 5 or greater than 5, you'll see "Text long enough" below the input field.

Also, each letter you entered is shown in a box below the input field.

By clicking each letter in a box, you can remove it. One by one.

This small project is a good exercise to understand how to use setState of React and JavaScript's basic syntax, including ES6.

### To run this project

"NPM start" to run this project

### Completed the tasks below

1.Create an input field(in App component)
with a change listener which outputs the length of the entered text below it
(e.g. in a paragraph).

2.Create a new component
(=> ValidationComponent)which receives the text length as a prop

3. Inside the ValidationComponent,
   either output "Text too short" or "Text long enough" depending on the text length
   ( e.g. take 5 as a minimum length)

4. Create another component (=>CharComponent)
   and style it as an inline box
   (=> display: inline-block, padding: 16px, text-align:center, margin: 16px, border: 1px solid black.)

5. Render a list of CharComponents where each CharComponent receives a different letter of the entered text
   (in the initial input field) as a prop

6. When you click a CharComponent, it should be removed from the entered text.

Hint: Keep in mind that JavaScript strings are basically arrays!
