# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Andy Cordero**

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/nine-diagnostic-crate?path=README.md%3A63%3A870

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
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Added gradient colors to buttons and heading
- [x] Letter changes to different color when a button is pressed

## Video Walkthrough (GIF)

When you pass eight rounds,

![x](https://cdn.glitch.global/b5fcb5be-6f8a-4e18-8955-371726d77f79/ezgif.com-gif-maker-2.gif?v=1647732869120)

When you make three mistakes,
![x](https://cdn.glitch.global/b5fcb5be-6f8a-4e18-8955-371726d77f79/ezgif.com-gif-maker.gif?v=1647732693526)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I utilized the following resources to complete my submission: W3schools and Modzilla for HTML, CSS, and JavaScript guides; StackOverflow for personal design assistance; and UIGradient for background, text, and button design.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I encountered a challenge when one of the buttons made a long beep when clicked. When I implemented two more buttons with different beeps in the game, I heard a long beep when I clicked one of the six buttons once while pressing the button. So I debugged the JavaScript file to see why the beep sounded so long when the button was clicked. Unfortunately, none of the features indicate the cause of the beep sound problem. When I recopied the beep function from the JavaScript instructions in the Prework project, 4 out of 6 buttons worked correctly. Now that I've changed the frequency map, for example, by adding two more keys and changing the pitch of each key, the button work normally, but not long. When I styled each button in the CSS file, I still heard a long beep when I clicked on one of the buttons. When I held down a key, I found that every time I clicked on a letter in the key for a second, the text was highlighted, and the beep sounded for a long time on release. I wanted to remove the text highlighting feature in the button by implementing the "user-select" property in the game button rule and setting it to "none" in the CSS file. After mounting, I heard a beep when I clicked the button. Therefore, I understand why clicking a button makes a long beep and how to fix it.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

I have some questions about CSS's responsive design now that I've finished the project. When I visit a website on my laptop, the layout includes various content such as interactive buttons, a complete navigation bar, and a message chat. However, the style is more compact and has a limited range of content on the phone, and some websites offer a mobile application to download. As I researched the various layouts from different devices with the same website, I discovered that most websites' responsive designs are accomplished mainly by CSS. CSS contains a handful of responsive properties that may be used to determine the layout of a website based on the display size. I found it essential since most web developers want the layout to appear beautiful on different size displays and be mobile-friendly. As a result, I'm looking forward to learning how to create responsive web designs with CSS and utilize its capabilities.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

If I had a few more hours to complete this project, I would have made the game infinite to see how far the player could get by appending a random number between one and six to the pattern array if the player correctly guessed the pattern. I would also add the game's scoreboard. For example, if the player guesses the pattern correctly, it will earn the number of points for each pattern. It will also utilize the high score function by using the max method to determine whether the player's current score exceeds the high score. I would provide the feature to prevent the player from clicking any buttons while the game displays the next pattern hint. In terms of design, I would include some placement choices for the six buttons in the two-by-three grid for large displays (e.g., computer, tablet) and three-by-two grid for small displays (e.g., phone) (e.g., phone).

## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/NrkPj7jv5RU)


## License

    Copyright Andy Cordero

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
