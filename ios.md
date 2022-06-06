# IOS note

## swiftUI
doc and cs193p

## UIKit
https://itisjoe.gitbooks.io/swiftgo/content/uikit/uikit_intro.html








## flow

```
(markdown/html) -> ast parser -> render+themeProvider+noteModifier -> typographer -> (display)

----
(markdown/html) -> ast parser -> xml    [preparsing by python, js etc.]

render+themeProvider+noteModifier -> typographer -> (display on iOS, MacOS)

```




- **ast parser** [universal]  -- # can be implemented by `Rust`
- **render** [ios/mac/android/web/win] 
- **typographer** [ios/mac/android/web/win]

