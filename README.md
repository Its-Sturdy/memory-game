# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Amimul Arnab**

Time spent: **8** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [X] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/3YB8DfR.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.youtube.com/watch?v=1Rq_LrpcgIM (How to use Random Numbers in Javascript)
https://www.youtube.com/watch?v=FNGoExJlLQY&t=3s (HTML Crash Course Tutorial)
https://en.wikipedia.org/wiki/Guitar_tunings (Use guitar tuning frequences and assigned Guitar Frequencies to the corresponding string notes)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    There were numerous challenges I faced while doing this project. For one, I know a little bit of HTML, CSS, and Javascript, but not enough to be able to work on a project. I watched a one hour crash course to build working knowledge on HTML and better understand the syntax. The most challenging part isn't HTML or CSS, but rather the backend which is Javascript. HTML and CSS are only the frontend which the user sees. However, all the logic and operations that happen are in the backend which is in the .js file. Thankfully, my background in C++ helped me understand the logic but it was challenging to apply the logic into the language the cpu understands. After completing the main objective, I attemped the optional objectives. The one I attemped was random order for the memory test. I knew that I have to use a random function generator but I didn't know the proper syntax for generating number values 1-4. I used youtube to help me find the correct syntax, but I added a random global varialbe and used that variable as a return function for my randomPattern() function and declared the pattern variable by calling the function in the pattern, which generates an integer between 1-4 instead of a float variable and it worked. I do have a solid foundation in using HTML, CSS and Javascript, but since this language is new to me, I lack the experience and practice to conduct these types of projects. In due time and through the summer course, I will be much more experienced in web development because this directly aligns in my future.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

   How do websites store data and information such as passwords, emails, and useful information?
     What kind of encryption do websites use and how does it work? 
     How does the front end communicate with the backend files in order for a webpage to function?
     How do URLs connect and keep the memory of data?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    I found the email about this internship opportunity very late. I found out on April 1st through my     campus directory emails and only had a day to work on it. The prework, even though 
    the main code is explained beautifully and easy to follow and understand, I wanted to play around       with the code to make the code as unique as possible and saw opportunities to further improve on the code. First thing I noticed is the pattern was predictable, so I created a function to use random buttons for memory test. I wanted to further build onto the fucntion and reset the order after a failed attempt in the memory test. If I had more time, I'd add images in the buttons, and add images in the page. I'd also reduce the time after each successful progress and fail the test if the user takes too long to answer the memory test. I would also add three attempts until it fails the test and add a timer and scoreboard. In other words, I'd attempt all the optional objectives if I had more time, at least a couple of hours to do it. Majority of programming is logic which is the difficult part but definitely possible. All that is needed is time. When I do solve a coding challenge such as a couple of the optional objectives I did do in this project, it felt rewarding and fun.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/UFr5liWAzOc)


## License

    Copyright [Amimul Arnab]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.