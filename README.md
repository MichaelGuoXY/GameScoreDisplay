# GameScoreDisplay
A Class written in Swift to help you easily use images to represent digits within certain area of UIView, additionally centered horizontally.

## How to use
Put ScoreDisplay.swift into your iOS project, and add "digit image" from 0 ~ 9 named "0.png" ~ "9.png" into your assets

### create an object of ScoreDisplay class
```swift
let scoreDisplayer = ScoreDisplay()
```
### then init with function setTargetForDisplay()
```swift
@IBOutlet weak var scoreDisplayView: UIView!

scoreDisplayer.setTargetForDisplay(scoreDisplayView)
```
Note that the scoreDisplayView is a UIView that you create on the storyboard or whatever
### finally just use function displayAnyScore() to display within certain area of your UIView
```swift
scoreDisplayer.displayAnyScore(12345678)
```

### image1
<img src="https://raw.githubusercontent.com/MichaelGuoXY/GameScoreDisplay/master/digits-images/image1.png">

### image2
<img src="https://raw.githubusercontent.com/MichaelGuoXY/GameScoreDisplay/master/digits-images/image2.png">

