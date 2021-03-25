# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: JESSABELLE RAMOS

Time spent: 4 hours spent in total

Link to project: https://glitch.com/edit/#!/pricey-pickle-nylon

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
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
! Winning the game: https://imgur.com/a/D6xOvZq
Losing the game after 2 mistakes (on 3rd): https://imgur.com/a/aKGKkqF
I couldn't get the gifs to embed. This is my solution :(



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I consider myself detail-oriented, someone who makes a conscious effort to identify and solve problems through both their causes and effects. However, in this assignment, it was to my disadvantage.

I found this project to be straightforward and simple to implement (with respect to the base assignment). However, in approaching the optional feature of failing after 3 mistakes (on the third), I struggled greatly due to a misunderstanding between the game logic and my implementation. Mainly, I assumed that the guess pattern would reset after each mistake. However this was not the case, instead the game continued at the latest guess such that you only had to press the next button in the sequence -- not start over. I had assumed that I had made an error in implementing the game logic and focused heavily on finding and fixing that error by debugging line by line, making small changes with respect to how I ASSUMED the game worked, rather than focusing on what the code actually said.

This further harmed me in terms of time -- I found this internship opportunity fairly late, and on top of midterms and extracurriculars at my school, I should have allocated my time differently to give this assignment the full attention I hoped to. 

With time running out and with few features implemented, I nearly undid the 3-strike feature in favor of simply finishing the project. Instead, however, I took a step back and reevaluated the code, giving great attention to what was actually happening in the game versus what I thought the code would do. I realized the error in my assumptions, reevaluated my perspective, and recognized that the game continued at the latest guess. 

In the end, I was not able to implement all the features I wished to. However, I prioritized completing the project and compromised on my vision. I was able to fix my error by “fixing” my focus and my perspective.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

This assignment was my first real introduction into front-end web development and using HTML and CSS, with Javascript to enhance the application and make it interactive. Even as an avid user of the internet, I know I haven’t seen the full extent of what can be done with web development, and working on this submission has stoked my curiosity by showing me the humble beginnings of front-end development.
I'm curious about the testing process of web development -- in Java, we test our applications to ensure they work as intended, but with web development, I assume that just “functioning” is not enough. What makes a web application "good"? How do you determine whether a website is fit to publish? 

Furthermore, how would I have finished this project with a client in mind to satisfy? What is the typical process for web design, and how do developers make it their own?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time, I would improve the user interface in terms of overall aesthetic, such as fonts, special buttons or a UI with buttons that looked like the physical Simon Says toy.
Furthermore, if possible, I would try to implement the following feature: after every round, another button is added to the screen, or the buttons change places (but the order stays the same)

I would also make this project competitive or social. To do this, I would make the game multiplayer in which players could compete to see who gets the longest sequence. This would be achieved by extending the clue pattern by adding a new number to the pattern with each new round. I would also implement a chat feature or keeping track of users’ highscores.

Finally, I would add difficulty levels (easy, medium, hard). The level of difficulty would affect: the time between clues or the implementation of a timer for each guess, the number of buttons increasing with difficulty, the difference in colors of buttons becoming more and more similar with increased difficulty, difference of tones for each button becoming more and more similar with increased difficulty, etc.



## License

    Copyright Jessabelle Ramos

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.