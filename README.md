# CSS Transformations Challenge nr 3

When hovered, move a div with a class of element on A-axis by 100% in 1 second. Apply Transitions.

### Points to remember 

##### Hover method:

.element:hover {
    transform: translateX(100%); /*Hover function */
}



##### The hover method is "called" in the .element class:

transition: transform 2s ease-in-out; /*target the hover function */
