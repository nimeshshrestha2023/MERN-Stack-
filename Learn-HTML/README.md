# HTML SEMANTICS: It is just nothing but the structured  HTML rule to be followed.
1. All the HTML tags should be in lowercase.
2. Add alt inside img tag.
3. Use kabab case for naming the html file name; eg. hello-world.html

# Form: 
1. Text: <input type="text">
2. Email: <input type="email">
3. Password: <input type="password">
4. Number: <input type="number">
5. Telephone: <input type="tel>
6. Range: <input type="range">
7. File: <input type="file" accept=".png , .jpg">
8. Radio: <input type="radio"> Radio
9. Checkbox: <input type="checkbox">
10. Data: <input type="date">
11. Time: <input type="time">
12. Datatime: <input type="datatime-local">
13. Textarea: <textarea>
14. Color: <input type="color">
15. Submit: <input type="submit">
16. <select>
        <option> option 1 </option>
    </select>


# CSS -> Cascading style sheet

-> Used for styling the web page, like color, font , positioning, spacing ...

***SYNTAX***    
<selector>{
    property: value;


}

***SELECTOR TYPES***
1. elements: h1, p, span (Lowest priority)
->
element-name{
    ...
}

2. class: elements > class Priority < id
->
.class-name{
    ...
}
3. id: Highest priority
->
#id-name{
    ...
}


# CLASS VS ID
-> Class should be used for CSS, Id should be used for JS
-> Class name can be used multiple times, Id must be unique.
-> Class name can be multiple; for eg: 
<p class="content text-color decorate >


CSS types(Usage):
1. Inline CSS (Highest priority than id)
2. Internal CSS
3. External CSS(Recommended)

# CSS PROPERTIES
1. color: 
- rgb(255,255,255); Range: 0-255
- hex: #0000000; Range: 0-9 , A,B,C,D,E,F
-hsl: 

# CSS TEXT PROPERTIES
- text-align: center, left , right, justify(it is generally used in the paragraph.)
- text-decoration: none | underline wavy / dotted / dashed / line-through;

- text-transform: lowercase, uppercase, capatalize;

- word-spacing: 10px;
- text-spacing: 10px;
- line-height: 10px / 1 / 2;
- text-shadow: -10px 0px 5px red; // horizontal vertical spread color;

# FONT PROPERTIES:
- font-family: font-name;
- font-size: 10px;
- font-weight: bold / lighter / normal;
- font-style: italic / oblique;

# BOX MODEL PROPERTIES
1. margin
- margin: 10px; // All side are same;
- margin: 10px 20px; // top-bottom left-right

- margin: 10px 20px 30px; // top left-right bottom;

- margin: 10px 20px 30px 40px; // top left bottom right


2. border: 5px solid/dashed/dotted color;

3. padding: 10px 20px 30px;


# Display properties

- display: none;
- display: block;  for display: block; it can have height and weight and covers full width
- display: inline; for display: inline, it can have only required height and width:
- display: inline-block; it includes height and width 

# display: flex;

- display: flex;
    flex-direction: row; /*row(default), column , row-reversed, column-reversed*/
    align-items: center; /*row, column , center*/
    justify-content: space-around; /*start, center, end, space-around, space-between, space-evenly*/

    /*NOTE: for display: flex; we can use flex-direction and justify-contents*/


# List Properties: 

- list-style: disc/circle/square/none/lower-alpha/upper-alpha

# Pseudo(Abstract or fake) Properties: 

- hover: 
- first-child:
- list-child:
- nth-child:
- disabled: 
- active:


# UNITS PROPERTIES:

- px(pixel);
- em(relative to parents);
- rem(relative to root);
- vh(viewing height); if height: 80vh; then it covers 80% of full screen;
- vw(viewing widht);
- in(inch);
- cm(centimeter);

# Overflow properties: 
-> When the paragraph , exceeds the box size limit then there occurs overflow case, then we have to use the css property "overflow";

-> auto, hidden, visible,scroll are the value of overflow property.

-> overflow-x: scroll and overflow-y: scroll are also some of the overflow properites.

# Position Properties: 

1. static(default)
2. relative(relative to parent selector)
3. absolute(relative to root)
4. sticky
5. fixed

# display: grid; Properties: 

- grid-template-areas:1fr 1fr;
- grid-template-areas:repeat(3,1fr);
- gap: 50px;
- row-gap: 50px;
- column-gap: 40px;

# Create variable in CSS

***SYNTAX:***
---your-variable_name:"value";

- Variables can be better implemented inside the root;

:root{
    --primary-color: color_name;
}

# Transform Properties:

- transform: translate(100px,75px) rotate(45deg) scale(1.5) skew(15deg)[Basically the parallelogram]
some of the properties of the transform.

# Animation Properties: 

- for using animation properties in css, we have to define it using @keyframe;

***SYNTAX:***
animation: animation-name duration timing-function delay iteration;  
animation: animation-name 5s ease-in-out infinite; 

@keyframe animation-name{

    0%{

    }

    25%{

    }

    50%{

    }

    75%{

    }

    100%{

    }

}

# Tailwind CSS:

- CSS Framework
- used for building UI rapidly
- Instead of writing CSS code, we use predefined utility classes directly in HTML.
- Highly customizable, works in dark mode.

- Just in time(JIT) compiler for faster builds.

 


























 