
![right](https://avatars2.githubusercontent.com/u/5214462?v=3&s=460)

# Lincoln Anderson
### Product Designer @352inc <br> Tweet: @brokenlinc

---

# hello [^1]

[^1]: I just learned about this stuff a couple of weeks ago. I'm no expert but I thought it was really cool and wanted to share it with you. It's definitely a fringe technology with subpar documentation. But if you're feeling intrepid, it can be a lot of fun. Thanks!

---

# Making Sketch Plugins
## using *CocoaScript*

---

![120%](http://bohemiancoding.com/static/images/home/app-icon@2x.png)
# What is *Sketch*?

---

![right 90%](http://bohemiancoding.com/static/images/home/app-icon@2x.png)
## *Sketch* is a graphic design app for OSX.
### It's recently become very popular with web designers.

---

# What is *CocoaScript*?

---

# CocoaScript
- It used to be called JSTalk.
- It's a scripting language for Mac OS X built on top of JavaScript.
- It has a bridge to Apple's Cocoa libraries.
- Build OS functionality with Javascript![^2]

[^2]: Actually a weird Javascript-hybrid language. You'll see.

---

### Cocoascript's biggest deviation from normal Javascript is Objective-C "bracket syntax".
### These two lines are equivalent!

```javascript
mydog.bark(5)

[mydog bark:5]
```

### They both call the ```bark``` method on the ```mydog``` object, with a parameter of ```5```.

---

## Sketch uses CocoaScript to support a system of *plugins*. 

---

# [fit] Let’s make one!

---

- **Mac Developer Library**
developer.apple.com/library/mac

- **JSTalk**
jstalk.org

- **JSTalk -> CocoaScript Migration**
github.com/sketchplugins/cocoascript-migration

- **Sketch Developer Support**
bohemiancoding.com/sketch/support/developer
