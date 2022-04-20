<a href="https://github.com/jkulba/Azul/">
    <img alt="The Azul Project" src="https://github.com/jkulba/Azul/blob/main/azul.png"
    width="150" height="150">
</a>

# Azul
DotNet C# 6 Worker Service.

## Changes
* Added a generic nuget.config file to resolve a nuget cache issue.

## Service Install

### Local Installation Directory
```pwsh
C:\USERHOME\.services
```

### Publish
```pwsh
dotnet publish --output "C:\USERHOME\.services\azul\"
```

## References
[Create Windows Service using a BackgroundService](https://docs.microsoft.com/en-us/dotnet/core/extensions/windows-service)
