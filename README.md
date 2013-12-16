### Jernau: a Light Table theme

A dark theme with rainbow brackets:

<img src="https://raw.github.com/Misophistful/jernau-lighttable-theme/master/jernau-lightable-theme.png">

(Tested as working in Light Table 0.5.x)

### Installation

Copy the css file to `/LightTable/core/css/themes/`, then update the `user.behavior` settings file with the following:

```clojure
  {:+ {:editor [(:lt.objs.style/set-theme "jernau")]}}
```

(To open the `user.behavior` file use CTRL+SPACE to open the Command Panel, then search for "User behaviors".)
