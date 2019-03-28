From The Odin Project's [curriculum](http://www.theodinproject.com/courses/web-development-101/lessons/html-css)

This is a The Odin Project mini-project on deconstructing and rebuilding an existing webpage (Google.com).

The focuses in this project are:
1. To familiarise myself with good implementation of HTML and CSS
2. An intro to using browser developer tools as a part of normal workflow to increase productivity.


Post completion:
    Interesting Skills/things Learnt:
        -Put a favicon next to the title in the head bar.
            -tag: <link>; attributes: rel="shortcut icon", type="image/..."(jpg/png/etc.), href="..."

        -Font Awesome
            -easy way to add different icons
            -used font awesome to add apps icon in navbar
        
        -CHROME DEV TOOLS!!!!!!

        -Keep footer at the bottom
            -make a container for all content and set position to relative and its height to 100% of the viewport (height: 100vh)
            -create a wrapper div for all content except the footer and set its height equal to the height of the footer
            -set the footer's position to absolute and (bottom: 0;)

        -used flexbox to position the "search' and 'I'm feeling lucky' buttons
            -probably not necessary for my purposes but google themselves position these buttons using flex and I gained some experience with it

    Reflection:

    This project took me longer than I expected or hoped. I was very caught up in wanting it to look exactly the way google's homepage does that I blocked myself from making a good start. Once I managed to set up a basic structure of how I thought it should look the ball started rolling and it became a lot easier to work on.
    Initially I got very confused looking at google's source code on chrome dev tools and trying to understand what was going on. This was also a block for me because I knew I was supposed use chrome dev tools to make styling my html easier. Eventually I got the hang of it and it made all the difference!!

    The most difficult part was definitley figuring out roughly how they implemented their search bar with a styled containing div around the text input field (with the borders of the input tag made transparent).

    I look forward to moving on to the progamming elements of web development.
