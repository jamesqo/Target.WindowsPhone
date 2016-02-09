# Windows Phone APIs for .NET Core

Creating a .NET Core library? Want to use native Windows Phone APIs? This project is for you.

## Getting Started

Just add this to your `project.json` file:

```json
"frameworks": {
    "wpa81": {
        "Target.WindowsPhone": "8.1.0"
    }
}
```

Want to use Windows Runtime APIs for Windows Phone 8? No problem:

```json
"wp80": {
    "Target.WindowsPhone": "8.0.0"
}
```

## License

[MIT](LICENSE)
