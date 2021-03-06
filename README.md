Litegrid
======
Litegrid in it's current form is an <b>extremely</b> flexible grid system. However, it is hoped Litegrid will eventually
evolve into an extensive framework that will enable you to take your projects from the sketching stages right through
to shipping the final product.

Prerequisites
=============

<ul>
<li>Ruby - Great guide for installing Ruby on Mac OSX http://net.tutsplus.com/tutorials/ruby/how-to-install-ruby-on-a-mac/ <br />- Guide for installing Ruby on Windows http://www.youtube.com/watch?v=WUdDdiu8kBs</li>
<li>SASS - http://sass-lang.com/</li>
<li>The ability to copy simple commands into the terminal</li>
</ul>


Why Choose Litegrid?
==================

<ul>
<li>It's extremely customizable</li>
<li>It contains two grid systems</li>
<li>Easily nest and offset your grid</li>
<li>It's semantic*</li>
<li>Superb browser support </li>
<li>It's lighting quick to use</li>
<li>Built using the preprocessor SCSS</li>
<li>Extensive documentation & support</li>
<li>It's not BootStrap</li>
</ul>

 *It's semantic in the way that it removes presentational classes. It is 100% your responsibility to create semantic class names.

The Syntax
==========
The syntax is effortless, there are no presentational classes (except the row class,
which you can easily attach to a HTML5 ```<section>``` tag). Other than this you will
choose your class names.

 ```
    <section class="row">
        <article class="blog">
            Content here
        </article>

        <aside class="sidebar">
            Content here
        </aside>
    </section>
 ```

It is literally down to you to make your class names more semantic and meaningful.

Getting Started
===============

Download/clone this repository and compile the SCSS into raw CSS via the method relevant to your platform. Eg. The Terminal if you're running OS X.

You can then open index.html in your chosen browser and see the proof of concept grid system.

I've released a screencast showcasing how to get started with the Litegrid grid system here:
http://www.youtube.com/watch?v=IkdhIdg1U60

There is also quick reference guides for you to refer to inside the style.scss & grid.scss files.

Browser Support
===============
Litegrid's grid has amazing cross browser support.

<ul>
<li><del>IE 8 +</del> IE 9 +</li>
<li>Firefox 3 +</li>
<li>Chrome ALL</li>
<li>Safari 4 +</li>
<li>*Opera 10 +</li>
</ul>

Litegrid's is supported all the way down to Opera 10 but users may experience
some minor subpixel rendering differences in older versions of Opera.
Litegrid is a project created & maintained by <a href="http://twitter.com/richmwatts">@richmwatts</a>
