# Blazor.Cordova

This project allows you to run a Blazor app inside a cordova application.

## Demo
If you're looking for the demo code from the Blog Post its inside the blog-demo folder

## Usage
Install package Bickellukas.Blazor.Cordova
```
$ dotnet add package Bickellukas.Blazor.Cordova
```

Modify index.html:  
Remove base href  
Adjust script references:
``` html
    <script src="framework/blazor.cordova.js"></script>
    <script src="framework/blazor.webassembly.js"></script>
```

Now you can use the published files in a cordova application