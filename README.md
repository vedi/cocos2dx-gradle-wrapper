Cocos2dx Gradle Wrapper
---

The wrapper allows you to use cocos2d-x java sources as subprojects of your project with gradle structure. 

Getting Started
---

1. Clone the repository to your gradle projects:
```
  git clone https://github.com/vedi/cocos2dx-gradle-wrapper.git cocos2dx
```
1. Add it to your `settings.gradle`, adding ':cocos2dx' to `include` section.
1. Create static link `cocos2d`, pointing to java sources of you cocos2d-x.
```
ln -s <COCOS2D-X LOCATION>/cocos/platform/android/java cocos2d 
```

It should work!


You're welcome to any feedback.


