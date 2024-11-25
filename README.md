# Error Handling #

** 01 - exe file not in the correct directory **
```
Unable to start program in <path>\DIP Coins Activity.exe
```

<b> Move the executable file to ```.\bin\Debug\net8.0-windows\``` </b>

** 02 - 'projects.assets.json' not found **

```
<path>\projects.assets.json not found. Run a NuGet package restore to generate this file.
```

<b> Go to Tools > NuGet Package Manager > Package Manager Console and simply run: ``` dotnet restore ``` </b>
