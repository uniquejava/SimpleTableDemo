# SimpleTableDemo

The book reads, "The content of table view now overlaps with the status bar", but I tested, at least in latest Xcode8.1(released earlier today), there is no such issue.

And Adding the code below in ViewControll.swift makes the app fullscreen, but it's a little ugly then.

```swift
override var prefersStatusBarHidden: Bool {
return true
}                                                      

```

The `basic` table cell contains a text label and imageView that we can use directly.
