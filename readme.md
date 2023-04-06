# Twitter Bird Browser Extension

![Twitter Bird](https://github.com/maciejwalkowiak/twitter-bird-extension/blob/main/icons/icon128.png)

Tiny extension that brings back the actual twitter logo and gets rid of the Doge dog from the upper left corner

## How to add this extension to your browser?

This extension is not published (yet) to Chrome Store. To add it to your browser:

1. Clone the repo:

```
$ git clone https://github.com/maciejwalkowiak/twitter-bird-extension
```

2. Run `make build`
3. Install extension:
- **Chrome**: Go to `chrome://extensions`, enable "Developer Mode" and load the unpacked extension from `build/chrome` directory.
- **Firefox**: Go to `about:debugging#/runtime/this-firefox` and load the temporary add-on from `build/firefox` directory.

Enjoy!

[Bird icons created by Freepik - Flaticon](https://www.flaticon.com/free-icons/bird)
