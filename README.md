# TextFieldDynamicWidth

SwiftUI TextField where the width is automatically made as small as possible. I used this in one of my projects and saw some people on Reddit were having trouble solving this problem. Just copy the TextFieldDynamicWidth.swift file to you project to use.

## Example

```swift
HStack(spacing: 0) {
  TextFieldDynamicWidth(title: "Type something here!", text: $editingText) { editingChange in
    // logic
  } onCommit: {
    // logic
  }.font(.title).multilineTextAlignment(.center)
  Text("This text will appear immediately to the right of the text field")
}
```

## Notes

I have 0 intention of maintaining this. I just wanted to help out those Redditors. If there is a problem or an improvement you want, make a pull request and I'll approve it.

Reddit post: https://www.reddit.com/r/SwiftUI/comments/eq1a9o/how_to_make_textfielduitextfield_change_width_and/
