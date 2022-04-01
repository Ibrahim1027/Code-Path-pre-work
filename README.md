# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Sory Sidibe

Time spent: **5** hours spent in total


Link to project:(https://glitch.com/edit/#!/noble-nervous-crocodile?path=script.js%3A1%3A0)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)
Here is a walkthrough of the Game!
![](https://i.imgur.com/Yi3lbJB.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[N/A]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
This project was very interactive and enjoyable to make, the step-by-step process was well thought out. Although the process is made simpler for the user, when it comes to coding, it will always get to the debugging phase. When I first finished the project, the first bug I noticed was that the start button would not disappear. It took me a while to find the missing detail where I had to make sure that the “hidden” attributes were correctly placed in the Html, CSS and JavaScript. After clearing that issue, It happened that my game would only play one tone and stop. Automatically, I knew that something was wrong with my code in JavaScript and I looked at all the functions to make sure they were the right ones and no matter how much I looked, I could not find any issues with the functions. It was very frustrating at first, so I decided to skim through the steps again and noticed the “guess” function where my game logic was a bit off. I went through the provided game logic and fixed my errors. After I made sure the original version worked, I decided to play around with the shapes, the number of Inputs, the sequences and the time.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I had always wondered how websites were made and how they make them so interactive. A few years ago I helped my stepdad to create a website through a website and I always thought that all websites were developed through the same process. That was until I got introduced to Computer Science. It was like seeing the stage “behind the scenes”. This project was created through Glitch which lets us create a webpage and let us become the “director of the scene”. Now my question is, how does glitch look like “behind the scenes” ? My project was made using Glitch, what was used to make glitch? What CSS properties were used? The questions just wouldn’t stop and that got me more excited about coding.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours, I would spend time on randomizing the sequences for each round which would be a function in JavaScript. Make the game faster each time a player would win to increase the difficulty . I would also spend time on the sound function. I took a look at the external link given for the sound function and it looked complex but not impossible. I would try to change the sound of the tiles for each round and create more melodic sequences. I believe that adding images would make it look more attractive and adding a help feature would make it more user friendly.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/e1734c2478ba40ed9c788cdb232ae24d)


## License

    Copyright [Sory Sidibe]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
