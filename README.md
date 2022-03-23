# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Vince Hernandez**

Time spent: **11** hours spent in total

Link to project: (https://wave-encouraging-viola.glitch.me/)

Code: (https://glitch.com/edit/#!/wave-encouraging-viola?path=README.md%3A10%3A7)

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Cursor turns into a pointer when hovered over buttons
- [x] Hovering over game buttons causes images to appear
- [x] Custom made assets using a pixel-maker website
- [x] Centered buttons and text
- [x] Moving background

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

**Required Features:**
![Required Features](https://media1.giphy.com/media/QWVdLFmHidA1wZpkCm/giphy.gif?cid=790b7611aa53fb22d74d2156a79bf2444b7df3dcd4ccfa1d&rid=giphy.gif&ct=g)

**Hover Effects:**
![Hover Effects](https://media0.giphy.com/media/WtFypijI04GoJ66eFm/giphy.gif?cid=790b7611341ca8c06a8d4d8c05c70192cc7234bd99c83a4b&rid=giphy.gif&ct=g)

**Random Pattern Each Time:**
![Random Pattern Each Time](https://media0.giphy.com/media/b8DL0IRwRczB5XFfSB/giphy.gif?cid=790b76116774955eb3e586365906804d280d886c632fe4e1&rid=giphy.gif&ct=g)

**Moving Background and Centered Elements:**
![Moving Background and Centered Elements](https://media4.giphy.com/media/UNCIdeqR2S1ndOxOZ4/giphy.gif?cid=790b7611d03ae8148bae4ccaf613f461c00e9415d4c3be7a&rid=giphy.gif&ct=g)

## Reflection Questions

1. **If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.** <br />
   -Stack Overflow <br />
   -DoFactory <br />
   -GeeksforGeeks

2. **What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)** <br />
   When creating this submission, one challenge I encountered was implementing the feature of creating a random pattern for the memory game,
   so that each game is unique and different from the last. To start, when attempting to implement and code in the given concept, the first
   conflict was getting the values in place for the pattern. Given the hint of using “math.random(),” I assumed that I wanted to generate a
   random number between 1-5, and put it in place for the pattern. But upon testing, I realized that I had to make a dynamic array, and push
   it into the code that holds the pattern (var pattern: []; ). Given this thought process, I first initialized an empty array, so that everytime
   the function is called, a new pattern shows up. I did this by just simply placing “pattern: []” at the start of the function so a “fresh”
   pattern is ready to use. I then decided to create the random number generator, and since I had five play buttons, I used
   “Math.round(Math.random() \*4 ) + 1” to give us values between 1-5. I then pushed those values into the array using “pattern.push” to grab
   the numbers generated, and put them in the respective variable. The last step I needed to achieve was stopping the function once the
   array hits eight values. So by using “for (var i = 0; i < 8; i++)” I was able to create a for-loop that reads the value of ‘i’ and
   continues to increment each loop until it is no longer less than 8, stopping the loop. Once everything is in place, the function is put
   into “startGame()” and is called when the player presses the “start” button. By thinking of each process individually and putting them
   together to make a working function, a random pattern is generated for the player to play, and a new pattern will also be generated if
   the player decides to play again.

3. **What questions about web development do you have after completing your submission? (recommended 100 - 300 words)** <br />
   After working on and completing my memory game, I noticed that I had to do some research on my own accord in order
   to implement just a few simple ideas. Upon researching and looking at many different websites, I was introduced to
   all sorts of different ways to implement the same feature. Different button styles, RGB values, ways to decorate a box.
   Because of this, questions that I had all revolved around the creative side of web development: How many different
   ways are there to create the same feature? How can I use these features to benefit my lifestyle? What are some ways to
   make each and every project unique? When thinking about these questions, it encourages me to make more of my own websites
   and make them each unique from the last. And the biggest question I have after completing this project goes to follow:
   What are the limitations to HTML, CSS, and JavaScript?

4. **If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)** <br />
   If given a few more hours to work on this project, my goal would be to continue adding small features to perfectly
   encapsulate the theme and vision I had imagined. To illustrate, while working on this project, I imagined a theme of
   pastel colors and a dreamscape-esque visual atmosphere, based on my favorite game “Omori.” By spending hours making
   pixel-sprites (hence the 5+ hours on the project), decorating the buttons, finding backgrounds and colors to match the
   theme, positioning buttons / texts to make it more visually appealing, and much more, I believe I achieved my goal to
   a big degree. However, those features primarily utilized only HTML and CSS. In the future, I want to increase my knowledge
   on JavaScript in order to create more visually interactive features for the user. For example, creating seamless transitions
   between buttons, or a fancy toggle button to switch between a “light” and “dark” website theme, or perhaps a more immersive
   background based on the cursor position, I want to utilize JavaScript to the fullest degree in order to make my future
   websites much more inline with my creativity.

## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.youtube.com/watch?v=rdfSkuotnPo)

## License

    Copyright [Vince Hernandez]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
