# Learn How To Use Basic HTML5
[intro]

### Video
[![How to use HTML5 Video](http://img.youtube.com/vi/4zZvQGRaQWQ/0.jpg)](http://www.youtube.com/watch?v=4zZvQGRaQWQ)

### The code

![HTML to HTML5 image](http://i.imgur.com/wM5FZdZ.png)

#### Original code

__HTML__

        <h1>Carl Sednaoui Resume</h1>
        <p class="big">714 Happy Street, New York City 10000</p>
        <div>
            <ul class="contacts">
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

        <style>
        h1 {
            margin-bottom: 5px;
        }

        h2 {
            margin-top: 0;
            font-size: 16px;
        }
        </style>