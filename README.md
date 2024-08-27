# Stream Deck Kit - Compatible Apps

This repository holds a list of iPadOS apps that are compatible with [Stream Deck Kit](https://github.com/elgatosf/streamdeck-kit-ipad). The listed apps will be showcased prominently in the [Stream Deck Connect](https://apps.apple.com/app/elgato-stream-deck-connect/id6474433828) app, which needs to be installed before using a Stream Deck.

Please read [the documentation](https://docs.elgato.com/ipad) to learn how to integrate Stream Deck Kit into your own app. 

## Add your app

If you have an app that supports Stream Deck devices via Stream Deck Kit, feel free to create a pull request that extends [compatible_apps.json](compatible_apps.json) and provides a logo. 

__Example__:
```json
{
    "title": "Your app name",
    "creator": "Your (company name)",
    "text": "A short text that describes what you can do with StreamDeck in your app.",
    "url": "https://apps.apple.com/de/app/your-app/id12345", // A link to the AppStore
    "logoPath": "logos/your_logo.png"
}
```
The logo should be a square with a size between 256px and 512px. Place it in the [logos](logos) folder and adjust `logoPath` according to its name.