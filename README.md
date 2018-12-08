# **FileLib** 

<img width="100" alt="img" src="https://cdn.jsdelivr.net/gh/stylekit/img/FileLib.svg">

- Open,Save,Delete,Create (CRUD)

### A few examples:

```swift
FileModifier.write("~/Desktop/temp.txt".tildePath, "test")
FileAsserter.exists("~/Desktop/temp.txt".tildePath)//Output: true
FileParser.content("~/Desktop/temp.txt".tildePath)//Output: test
```
