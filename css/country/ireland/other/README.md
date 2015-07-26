Questions

- [What are CSS Pseudo-elements](#What are CSS Pseudo-elements) 


## What are CSS Pseudo-elements

Syntax

The syntax of pseudo-elements:

selector::pseudo-element {
    property:value;
}

Examples

p::first-line {
    color: #ff0000;
    font-variant: small-caps;
}

p::first-letter {
    color: #ff0000;
    font-size: xx-large;
}


h2::before {
    content: url(smiley.gif);
}

h2::after {
    content: url(smiley.gif);
}

::selection {
    color: red; 
    background: yellow;
}