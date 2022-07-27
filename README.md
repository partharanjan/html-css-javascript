# CSS
## How many way you can use CSS
CSS syntax is same as key value pair
word:meaning
key:value : dictonary
styleName:styleValue

color:red;
font-size:12px;

<div></div>
<span></span>
<p></p>

1. Inline - when we write the css in same html element
    <div style="color:red"></div>
2. Internal : add the css inside the HTML page
    <style>
            // add your css code
    </style>
    <p style="font-size:12px;color:pink">Hi</p>
    <p style="font-size:12px;color:pink">Bye</p>

    block{
        styles
    }

    assign this block to the html element

    mystyle{
        font-size:12px;
        color:pink;
    }

    bold{
        font-weight:bold;
        color:red;
    }

    Add the class
    <p class="mystyle">Hi</p>
    <p class="mystyle" style="font-weight:bold;">Bye</p>
    <p class="mystyle bold"></p>

    Priority
    <p class="mystyle">Hi</p>
    <p class="mystyle" style="color:red;">Bye</p>
    <p class="bold mystyle"></p>

3. External : add/reference outer-side css files to your HTML page

<link href="path to the external css" rel="stylesheet"/>

#Selectors
to access the HTML element into CSS style, we have to use selector

1. element - jsut like your HTML element
2. class - create styles and shared with multiple HTML elements
    to create a class css user have to use .(dot)
3. id - create style for specific HTML element.
    to create a id css for element we have to use #(hash)