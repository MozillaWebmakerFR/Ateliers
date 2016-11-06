##Workshop description
Participants modify the HTML and CSS codes of an existing project.
(And possibly the Javascript code, according to the chosen project.)

__Note__: it's recommended to teach the __“HTML Puzzle Game: introduction to HTML tags”__ before, so participants would have become familiar with HTML tags, their meanings and the basic structure of a HTML page.

##Audience, duration, equipment
* This workshop is made for beginners and literate participants, no technical prerequisite is needed.
* Up to four participants per mentor.
* 1 or 2 participants per computer.
* Duration: 1 hour to 1 hour and 1/2.
* Equipment: computers (only a browser is needed) and Internet connection.

##Key notions
* What is a HTML tag?
* What do these HTML tags mean?
* The basic structure of a HTML page.
* What is CSS?
* The meaning of some CSS properties that the participants will modify.

##Sequences
__Part 1 : preparation and introduction__

1. Before the workshop, the organiser install [Web Developer](https://addons.mozilla.org/en-US/firefox/addon/web-developer/) Add-on on her/his computer.
2. Open the browser and go to a Website chosen according to the audience.
3. With “Web Developer” tool: disable all CSS styles and explain the role of the CSS in a Web page appearance.

__Part 2 : play with Mozilla Timble__

* __Introduction__
    1. Go to [Mozilla Thimble](https://thimble.mozilla.org/fr/) Web page.
    2. Choose “Keep Calm and Carry On” project.
    3. Explain the two parts: code is on the left and display is on the right. Code modifications are displaying in real time.
    4. Explain the HTML tags and structure, and how to write comments.
* __Modify the HTML code__
    1. Work with the Editor part on the left, on the __“index.html”__ page.
    2. Modify the title `h1` (lines 18 to 22).
    3. Add a paragraph after the title: `<p>`Your text here.`</p>`
    4. Potentially modify the image: change `src="crown.svg"` by `src="another URL here”` (line 15).
*__Modify the CSS code__
    1. In the Editor, select __“style.ccs”__ page.
    2. Modify some properties of the elements `body`:
        * the background (line 2)
        * the text color (line 3)
        * potentially the font-family (line 4)
        * the text alignment (line 5)
        * potentially the internal margins `padding` (line 6)
    3. Modify some properties of the elements `wrapper`:
        * margins, the size and the color of the border (lines 9 to 14)
    4. Modify some properties of the elements `h1`:
        * the font size (line 17)
        * the letter spacing (line 18)
        * the title case: `uppercase` to `lowercase` (line 19)
        * the text weight (line 20)
        * potentially the margins (line 21 and 22)

__Part 3 : modify the CSS of a Website with the “Inspector Element” tool__ (Optional)

1. Open the browser and go to a Website chosen according to the audience.
2. Click right with the mouse and select “Inspect element”.
3. Select a colored background with the “Pick an element from the page” arrow.
4. In the column on the right, in __“Rules”__ tab: identify the `background` CSS property and modify its value.
5. Tell the participants they have modified the Website! And then explain why it is only a local modification made on their computer.

##Links
* [Mozilla Webmaker](http://webmaker.org)
* Tutorial to build the HTML cubes: [HTML Puzzle Box](https://yopdesign.makes.org/thimble/LTQ5ODQ2NjU2MA==/html-puzzle-box)
* MDN – Mozilla Developer Network: [The HTML Structuring the Web](https://developer.mozilla.org/en-US/Learn/HTML)
