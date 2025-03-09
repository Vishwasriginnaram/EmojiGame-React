
In this project, let's build an **Emoji Game**.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/emoji-game-output-v2.gif" alt="emoji-game-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Completion Instructions

<details>
<summary>Functionality to be added</summary>
<br/>

The app must have the following functionalities

- Initially, the _Score_ and _Total Score_ for the current game should be **0**
- When an **Emoji** is clicked,

  - If it is not the same as any of the previously clicked emojis, then the _Score_ should be incremented by one
  - If all the emojis are clicked exactly once

    - [Won Game](https://assets.ccbp.in/frontend/content/react-js/emoji-game-won-game-lg-output.png) view should be displayed

  - If it is the same as any of the previously clicked emojis
    - [Lose Game](https://assets.ccbp.in/frontend/content/react-js/emoji-game-lose-game-lg-output.png) view should be displayed
  - If the score achieved in the current game is higher than the previous scores then the _Top Score_ should be updated accordingly

- When the _Play Again_ button is clicked, then we should be able to play the game again
  - The _Score_ value should be reset but not the _Top Score_ value
- The `EmojiGame` component receives the `emojisList` as a prop. It consists of a list of emoji objects with the following properties in each emoji object

  |    Key    | Data Type |
  | :-------: | :-------: |
  |    id     |  Number   |
  | emojiName |  String   |
  | emojiUrl  |  String   |
