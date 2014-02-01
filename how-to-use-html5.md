# Learn How To Use Basic HTML5
[intro]

### Video
In this 17 minute video, Rob (a Thinkful mentor) and Carl (a Thinkful employee pretending to be a student) will walk you through basic HTML and HTML5 tag.

Throughout the video you'll learn about some of the challenges beginners run into when learning HTML. You'll also get a basic understanding of a few HTML5 tags and how to implement them.

[![How to use HTML5 Video](http://img.youtube.com/vi/4zZvQGRaQWQ/0.jpg)](http://www.youtube.com/watch?v=4zZvQGRaQWQ)

### The code

HTML
[![HTML to HTML5 - HTML Image](http://i.imgur.com/QLoWimz.png)](http://i.imgur.com/QLoWimz.png)

CSS
[![HTML to HTML5 - CSS Image](http://i.imgur.com/ETQrvTJ.png)](http://i.imgur.com/ETQrvTJ.png)

#### Original code

[View the JS Fiddle here](http://jsfiddle.net/carlsednaoui/759qz/)

__HTML__

        <h1>Carl Sednaoui Resume</h1>
        <p class="big">714 Happy Street, New York City 10000</p>
        <div>
            <ul class="contact">
                <li><a href="http://www.twitter.com/carlsednaoui">@carl</a></li>
                <li><a href="mailto:me@thinkful.com">email</a></li>
                <li><a href="http://www.thinkful.com/">website</a></li>
            </ul>
        </div>


        <div>
            <div id="big-title">Professional Experience</div>
            <div id="big-title-2">Thinkful - Marketing Engineer</div>
            <p>
                Do cool videos
                <br>Check youtube
                <br>Pet the office cat
            </p>
            
            <h3>Web Developer - Consultant</h3>
            <ul>
                <li>Do cool videos</li>
                <li>Check youtube</li>
                <li>Pet the office cat</li>
            </ul>
        </div>

        <div>
            <h1>Education</h1>
            <h2>Hacker School - Summer 2013</h2>
            <ul>
                <li>Build cool plugins</li>
                <li>Code code code</li>
                <li>Meet great developers</li>
            </ul>

            <h2>Hacker School - Summer 2011</h2>
            <ul>
                <li>Build cool plugins</li>
                <li>Code code code</li>
                <li>Meet great developers</li>
            </ul>
        </div>

__CSS__

        .big {
            font-size: 20px;
            font-weight: bold;
        }

        .contact li {
            list-style: none;
            float: left;
            margin-left: 10px;
        }

        .contact:after {
            content: "";
            display: table;
            clear: both;
        }

        #big-title {
            font-size: 20px;
            font-weight: bold;
        }

        #big-title-2 {
            font-size: 20px;
            font-weight: bold;
        }


#### Final code

[View the JS Fiddle here](http://jsfiddle.net/carlsednaoui/s2rJa/)
__HTML__ 

        <header>
            <h1>Carl Sednaoui Resume</h1>
            <h2>714 Happy Street, New York City 10000</h2>
            <nav>
                <a href="http://www.twitter.com/carlsednaoui">@carl</a> 
                <a href="mailto:me@thinkful.com">email</a> 
                <a href="http://www.thinkful.com/">website</a>
            </nav>
        </header>

        <section>
            <h1>Professional Experience</h1>
            <h2>Thinkful - Marketing Engineer</h2>
            <ul>
                <li>Do cool videos</li>
                <li>Check youtube</li>
                <li>Pet the office cat</li>
            </ul>
            
            <h2>Web Developer - Consultant</h2>
            <ul>
                <li>Do cool videos</li>
                <li>Check youtube</li>
                <li>Pet the office cat</li>
            </ul>
        </section>

        <section>
            <h1>Education</h1>
            <h2>Hacker School - Summer 2013</h2>
            <ul>
                <li>Build cool plugins</li>
                <li>Code code code</li>
                <li>Meet great developers</li>
            </ul>

            <h2>Hacker School - Summer 2011</h2>
            <ul>
                <li>Build cool plugins</li>
                <li>Code code code</li>
                <li>Meet great developers</li>
            </ul>
        </section>



__CSS__

        h1 {
            margin-bottom: 5px;
        }

        h2 {
            margin-top: 0;
            font-size: 16px;
        }

### Resources
Here are a few resources to help you continue your learning.

Short-form resources

- [Web Platform's HTML Tutorials](http://docs.webplatform.org/wiki/html/tutorials)
- [HTML5 Flowchart](http://html5doctor.com/downloads/h5d-sectioning-flowchart.png)
- [Designing a blog with HTML5](http://html5doctor.com/designing-a-blog-with-html5/)

Long-form resources

- [CodeCademy basic HTML track](http://www.codecademy.com/tracks/web)
- [Dive into HTML5 book](http://diveinto.html5doctor.com/)
- [Udacity HTML5 game development course](https://www.udacity.com/course/cs255)
