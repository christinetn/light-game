# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Christine Nguyen

Time spent: 3.5 hours spent in total

Link to project: https://glitch.com/edit/#!/bitter-dot-organ

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
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![start_stop_func](https://user-images.githubusercontent.com/71248843/112253787-97484180-8c1c-11eb-914d-c931675101e8.gif)


![walkthrough](https://user-images.githubusercontent.com/71248843/112252839-fc029c80-8c1a-11eb-9968-239ec681d53a.gif)


![check_game_over](https://user-images.githubusercontent.com/71248843/112253795-9c0cf580-8c1c-11eb-9af4-0a94a1bf6f66.gif)




## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

I used an example video of a similar light up memory game to see how the game should actually mimic and to get inspiration. I also used some YouTube to help deepen my understanding of certain topics.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

A challenge I had encountered was working with certain methods used in the game mechanics due to my unfamiliarity. For example, I did not understand the functions of some methods such as createOscillator and createGain. To overcome this issue, I made sure to understand the purpose of each method and step. I made sure to read the explanations provided by CodePath since they acted as a good reinforcement aid. I also made sure to develop a deeper understanding of the methods used by looking for extra information from outside resources such as YouTube. I did not move on to the next step until I fully understood the current step I was at.

Certain problems I had were due to light and color inconsistencies. For example, one particular instance I had was that the first tone did not light up. To overcome this issue, I had to go back to the code and analyze it. I had to reason with myself where the root of the problem would be. I reasoned that the issue must have stemmed from the action of the button in the HTML file or the color declaration of each button in the CSS file. The issue turned out to come from the CSS file due to incorrect button naming where each color was declared. This was a careless error that I easily overlooked. Despite my struggles due to having little experience working with game development and some knowledge of JavaScript, it was overall a good learning experience.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

After completing my submission, I have questions on how to succeed as a web developer as well as how to successfully build skills in web development. I am wondering what essential characteristics and skills are needed to be successful in web development. I am also looking for advice on how to create a smooth design process; I question how long and complex the duration of the design process should typically be. In terms of developing skills, I question what are the best ways one can improve on web development in addition to personal projects. Is it recommended to take a web development course? I also have questions on what recommended strategies are needed to successfully collaborate with peers.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

If I had a few more hours to work on this project I would transform the game by making it more unique. For example, I would add more design and style to the game buttons and tones. Besides making it more visually pleasing, I would also enhance certain features as well as add more features. For example, instead of having a drop down to say the game is over, I would enhance this feature by making it more visible. I would have a large game over text appear instead to make the user more aware of the game state. Additionally, I think it would be very fascinating to create a longer and more complex game mode. I would make it more complex by increasing the speed of the pattern playback. I also would randomize the pattern and increase the pattern to maybe 20 consecutive sounds or tones. Since the number would increase, I would attempt to create a strike system that marks a game over as three strikes.

## License

    Copyright Christine Nguyen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
