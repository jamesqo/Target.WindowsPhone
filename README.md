# Windows Phone APIs for .NET Core

<img src="http://i.imgur.com/5dzr6Wi.png" width="30%"/>

Creating a .NET Core library? Want to use native Windows Phone APIs? This project is for you.

## Getting Started

Just add this to your `project.json` file:

```json
"frameworks": {
    "wpa81": {
        "dependencies": {
            "Target.WindowsPhone": "8.1.0"
        }
    }
}
```

That's it! Then, you can write something like:

```csharp
using System;
using System.Collections.Generic;
using Windows.UI.Xaml;

public class MyApp : Application
{
    public MyApp()
    {
        Console.WriteLine("Hello, world!");
    }
}
```

and have it compile.

## Related Projects

- [Target.Windows](http://github.com/jamesqo/Target.Windows) - use Windows 8 APIs from .NET Core
- [Target.WindowsRuntime](http://github.com/jamesqo/Target.WindowsRuntime) - use Universal 8.1 APIs from .NET Core

## License

[MIT](LICENSE)
