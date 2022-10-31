## Read 13

### Why would a developer use local storage for a web application?

* Using local storage in our browser is extremely easy. You only have to type setItem and getItem. Basically you can store the state of your interface pretty seamlessly and that what makes it such a powerful tool.

### What information should not be stored in local storage?

* You should never use local storage to save your personal information such as social security number, passwords etc. If you do it you will run into the risk of your information being available to whoever can hack your computer.

### Local storage can store what type of data? How would you convert it to that type before storing?

* In the local storage you can only store strings. However, according to the article "You can work around this by using the native JSON.stringify() and JSON.parse() methods:"

## Sources

* https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/