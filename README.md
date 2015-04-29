# Ionicons.swift
Use [Ionicons](http://ionicons.com/) in you swift projects. The similar to [FontAwesome.swift](https://github.com/thii/FontAwesome.swift)

## Installation

- Drag and drop `Ionicons.ttf` and `Ionicons.swift` files into your project

## Examples

### Ionicons icon in label
```swift
label.font = UIFont.ioniconOfSize(200)
label.text = String.ioniconWithName(Ionicons.SocialGithub)

let attributes = [NSFontAttributeName: UIFont.ioniconOfSize(20)] as Dictionary!
```

### Ionicons icon in button
```swift
button.titleLabel?.font = UIFont.ioniconOfSize(30)
button.setTitle(String.ioniconWithName(.SocialGithub), forState: .Normal)
```

### Ionicons icon as navigation bar item
```swift
leftBarButton.setTitleTextAttributes(attributes, forState: .Normal)
leftBarButton.title = String.ioniconWithName(.SocialGithub)
```

### Ionicons icon as toolbar item
```swift
toolbarItem.setTitleTextAttributes(attributes, forState: .Normal)
toolbarItem.title = String.ioniconWithName(.SocialGithub)
```


## Requirements

iOS 7 or later.

## License
- Ionicons.ttf file licensed under [MIT](http://opensource.org/licenses/MIT)
- Ionicons.swift licensed under [MIT](http://opensource.org/licenses/MIT)
