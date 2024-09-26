# swift-2048
==========
A port of the popular 2048 game to Apple's Swift language.

## Overview

swift-2048 is a working port of the original [iOS-2048](https://github.com/austinzheng/iOS-2048) created by Austin Zheng. This version of 2048 is written entirely in Swift and does not rely on SpriteKit, mimicking the original Objective-C implementation. The game follows the same mechanics as the original 2048, where players combine tiles by swiping to reach the ultimate goal of creating a tile with the number 2048.

This project was initially created when Swift was still new, and while I'm no longer actively developing new features, bug fixes and updates for compatibility with the latest versions of Swift will be addressed. Contributions are welcome.

If you're looking for more advanced Swift projects, feel free to check out my Clojure interpreter project, **[Lambdatron](https://github.com/austinzheng/Lambdatron)**.

## How to Play
------------

- Tap the button to start the game.
- Swipe in any direction to move the tiles.
- Combine tiles of the same value to sum them up and try to reach 2048!

## Requirements
------------

- Xcode 7.0 or later.
- An iOS simulator or an actual iOS device running iOS 9.0+.

## Installation Instructions

To run swift-2048 on your local machine:

1. Clone the repository:
    ```bash
    git clone https://github.com/austinzheng/swift-2048.git
    ```

2. Open the project in Xcode:
    ```bash
    open swift-2048/swift-2048.xcodeproj
    ```

3. Build and run the project on the iOS simulator or a connected device:
    ```bash
    xcodebuild -scheme swift-2048 -destination 'platform=iOS Simulator,name=iPhone 11'
    ```

4. Swipe on the screen to start playing!

## Contributing
------------

Contributions are always welcome! If you'd like to add new features or fix bugs, feel free to submit a pull request. Please ensure that your code is well-documented and follows Swift best practices. For major changes, consider opening an issue to discuss what you would like to change.

Steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## Bug Reports and Feedback
------------

If you encounter any issues or bugs, please submit them via the Issues section on GitHub. Include a clear description of the problem, steps to reproduce, and screenshots if possible.

For other inquiries, feel free to open a discussion or reach out via email.

## Thoughts on Swift
------------

Swift is a well-designed language that has evolved significantly since its inception. While it offers many modern programming conveniences, it still holds a lot of potential to bring mainstream programming closer to functional paradigms like those in ML (although this may happen gradually, and with some resistance).

For my early thoughts on Swift, check out the git history for this `README.md`.

## License
------------

(c) 2014-2015 Austin Zheng. swift-2048 is released under the MIT license. See the [LICENSE](LICENSE) file for details.

The original 2048 game was created by [Gabriele Cirulli](http://gabrielecirulli.com/). You can find the original game at [2048](http://gabrielecirulli.github.io/2048/). The game was inspired by "Threes" by Asher Vollmer.

---

This updated README provides more detailed and clear instructions for running and contributing to the project, offers a more engaging and informative "Thoughts on Swift" section, and makes the game more accessible to new developers and users.
