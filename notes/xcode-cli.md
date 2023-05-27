
# Building Xcode via Command Line

Run
```
sudo xcode-select -s /Applications/Xcode.app/Contents/Developer
```

Then

```
xcodebuild -scheme OnlineJobsPH build -configuration Debug -sdk iphonesimulator
```