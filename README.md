# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Farhin Bhuiyan

Time spent: 10 hours spent in total

Link to project: 
Live Site - https://animated-messy-singer.glitch.me
Code - https://glitch.com/edit/#!/animated-messy-singer

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
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

Gif that shows if player won
![](https://i.imgur.com/NtCCAYo.gif)

Gif that shows if player lost
![](https://i.imgur.com/vQq4pYz.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

    https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
https://www.w3schools.com/js/

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    One particular challenge I faced when creating this submission was implementing the math.random function to allow for the player to have a different
sequence each time they press start. To overcome this challenge I had to think back to times when I had used similar applications/functions for different projects. Thus, I reflected on my experience working in python and using the function random.randrange. This function is similar to the one used in javascript as it also generates a random set of numbers from a specified range. However, since the two are completely different coding languages, the syntax and practical implementation of the two differ greatly. Therefore, I still had to do outside research on how to apply math.random in javascript. From this research, I learned that I can not simply call on the random function like it is typically done in python, but define it within another created function and then call back on it when running the game. Nonetheless, having this background knowledge and connecting my prior experience with this new one was pivotal in allowing me to quickly and efficiently make changes to my code. Teaching me that the only true way to make progress is to not simply learn skills separately but to make connections and build upon the foundation that you already have. This is a skill that I plan to incorporate throughout my career in computer science. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    After creating this submission, I would like to learn more about updating my graphics when it comes to website development and better utilizing CSS. For instance, this assignment required us to create a light and sound 
memory game where the user had to press buttons based on the corresponding sound. However, there is a simple background and only a set number of buttons. Despite this simple layout and graphics, it was difficult to incorporate complicated and realistic designs. This made me fascinated and awe of website and video game developers
that can incorporate such complex and realistic graphics without diminishing the functionality of the application. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)  

    If I had a few more hours to work on this project, I would dedicate them to incorporating outside images and sounds into the game. Based on my previous knowledge and
research I knew how to embed outside images on an HTML file, but I had difficulty working these images into the variables already in place so that they only showed up 
only after being clicked. Creating this game was a rewarding experience as it pushed me to brush up on my front-end experience. This 
past semester, I have been taking Discrete Structure which has piqued my curiosity for backend development such as working with databases, servers, and APIs. Thus, I would be interested in incorporating my back-end knowledge when it comes to creating a website. 


## Interview Recording URL Link

[My 5-minute Interview Recording](https://vimeo.com/695082011)


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.