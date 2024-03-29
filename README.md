# Lightweight Typing Test Game
![main](https://user-images.githubusercontent.com/48349453/226576755-9b2382a3-2220-4b80-b21f-63ff50525884.png)


This is a lightweight typing test game, where you can test your typing speed with 4 different types of typing tests - 10 words, 25 words, 50 words, and 100 words. The typing speed is calculated using the `performance.now()` method, which gives accurate responses.

Words used in the game are generated using the [Random Words](https://github.com/apostrophecms/random-words) package.

The files are structured using the Model-View-Controller (MVC) architecture.

The words per minute (WPM) is calculated using the average word length that is currently presented in the game, which gives a more accurate WPM.

![main3](https://user-images.githubusercontent.com/48349453/226577282-11a6458f-9e44-4b0a-be72-15cdccacaddc.png)


## How to Play

1. Clone the repository to your local machine.
2. Run npm install.
3. Run npm start.
4. Select the type of typing test you want to take - 10 words, 25 words, 50 words, or 100 words.
5. Start typing the words that appear on the screen.
6. Your typing speed in words per minute (WPM) will be calculated and displayed at the end of the test.

## Technologies Used

- JavaScript
- HTML
- CSS
- [Random Words](https://github.com/apostrophecms/random-words) package

## Credits

This game was created by Eros Karm.

The Random Words package was created by [ApostropheCMS](https://github.com/apostrophecms).
