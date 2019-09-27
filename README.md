# How to active dynamic new theme in BlazorWasm app
By [Kelvin Binh](https://github.com/kelvinbinhsd)

The simple project demonstrates how to active dynamic new theme in BlazorWasm app 

> Usage with careful: The project is in experimental research about Blazor WASM with .NET Core 3.0 SDK

## Screenshots

<details>
  <summary>Default Theme</summary>
  
  ![dashboard](Dashboard-Default-2019-09-25%20at%209.51.54%20PM.png?raw=true)
  
  ![news-feed](NewsFeed-Default-2019-09-25%20at%209.55.55%20PM.png?raw=true)
  
</details>

<details>
  <summary>RainyDay Theme</summary>
  
  ![dashboard](Dashboard-RainyDay-2019-09-25%20at%209.56.58%20PM.png?raw=true)
  
  ![weather-summary](WeatherSummary-RainyDay-2019-09-25%20at%209.57.39%20PM.png?raw=true)

</details>

<details>
  <summary>Redwood Theme</summary>
  
  ![dashboard](Dashboard-Redwood-2019-09-25%20at%209.58.39%20PM.png?raw=true)
  
  ![temperature](Temperature-Redwood-2019-09-25%20at%209.59.11%20PM.png?raw=true)

</details>

# Table of contents

- [Up And Running](https://github.com/kelvinbinhsd/blazor-dynamic-themes-sample/blob/master/README.md#up-and-running)
- [Switch to a theme](https://github.com/kelvinbinhsd/blazor-dynamic-themes-sample/blob/master/README.md#switch-theme-test)

## Up And Running

1. Install the latest [.NET Core 3.0 SDK](https://dotnet.microsoft.com/download/dotnet-core/3.0) release.

2. Build project and all of its dependencies.

   ```dotnetcli
   dotnet build
   ```
3. Or run run source code without any explicit compile or launch commands
   ```dotnetcli
   dotnet run
   ```
4. From browser, open [https://localhost:5001](https://localhost:5001)

## Switch Theme Test

To switch an existed themes (`Default`, `RainyDay`, `Redwood`), simply changing value of `activeTheme` from `./wwwroot/sample-data/settings.json` file

```json
{
    "activeTheme": "Default"
}
```

