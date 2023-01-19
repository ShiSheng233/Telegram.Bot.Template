# Telegram.Bot.Template

A template for creating Telegram bots using the [Telegram.Bot](https://www.nuget.org/packages/Telegram.Bot/) library.

.NET 6.0 is our target.

## Getting Started

1. Click the `Use this template` button to create a new repository from this template.

2. Modify `BotToken` field in `appsettings.json`.

3. Build and run your project.

## Build instructions

```bash
dotnet publish -c Release -r win-x64 --self-contained true

# or

dotnet publish -c Release -r linux-x64 --self-contained true
```

You can use any other runtime identifier (RID) supported by .NET Core.

It's recommended to use `-p:PublishReadyToRun=true` or `-p:PublishSingleFile=true`.

## License

MIT License