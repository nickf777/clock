Learning how to make a JavaScript clock using HTML, CSS, and JS with help from the Web Dev Simplified Tutorial.

New things I've learned so far:

    - You can use variables in CSS. This might have been particularly useful in some of my previous projects.
        - They are also referred to as custom properties, which allow a value to be stored in one place and referenced in multiple other places.
        - They also have the benefit in that they can be semantic identifiers 
        - Typically you declare them on the :root pseudo-class 
            :root {
                --main-bg-color: brown;
            }
            .one {
                background-color: var(--main-bg-color)
            }
    - The HTML data attribute is used to associate the JS data with a particular element. In this case we use it to associate the hour, minute, and second hand with the ratios that correspond to them.
    - The JavaScript for this is interesting! Some new things I learned:
        - setInterval(setClock(), 1000): is used to call the function every second to provide real time updating of the DOM
        - Using the ratios acquired through Date() to calculate the rotation of the clock

What I'd like to do moving forward:
    - Really break down this assignment using the Feynman Technique to ensure that I completely understand all aspects of the project and can explain them in comprehensible terms
    - Integrate this analog clock into my "To-Do List" project without the help of the tutorial.