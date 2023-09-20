### Ques2 Explain the purpose of comments in HTML and provide an example of how to use comments in an HTML document?

- Comments are useful when you want to write something about the code but you do not want to run that 
or show in the output.

- Comments are basically for humans, you write comments for your future self or for other developers who 
might work on the same codebase.

- In HTML we can create a comment as shown below and the browser will not display that on the screen.This means that they are not displayed on the page when it is rendered. However, they are still visible to anyone who views the page source code.


 An HTML comment begins with <! –– and the comment closes with––>
- Types of comments are:
    - **Single-line comment:**  Single line comment is given inside the ( <!–  comment –> ) tag.
    - **Multi-line comment:** Multiple lines can be given by the syntax (<!– –>), Basically it’s the same as we used in single line comment, difference is half part of the comment (” –> “), is appended where the intended comment line ends. 
    - **Using <comment> tag**: There used to be an HTML <comment> tag, but currently it is not supported by any modern browser.



  ### Example of comments : 
        <!DOCTYPE html>
        <html>
        <body>
        <!--This is single line comment i can write anything which help me -->
        <h2>This is single line comment</h2>
         <!-- This is
         multi-line
         comment that will help me and others to read and understand 
         the code to the computer and human-->
         <h2>This is multi-line comment</h2>
         </comment>
         <h2>This is a comment using</h2>
         </body>
         </html>


