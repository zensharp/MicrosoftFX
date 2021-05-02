# MicrosoftFX
[DocFX](https://dotnet.github.io/docfx/) template inspired by Microsoft's Documentation theme.
This is an override of the default template so you need to enable both in the `docfx.json`.

## Demo
You can view a demo DocFX project with this template [HERE](https://andrewmjordan.github.io/MicrosoftFX/).

## Install
1. Download the source or the zipped file from the [releases](https://github.com/andrewmjordan/MicrosoftFX/releases).
2. Create a `templates` folder in the root of your DocFX directory.
3. Copy the `microsoftfx` folder to the `templates` folder.
4. Update the `docfx.json` configuration to include the template:
    ```json
    {
        "template": [
            "default",
            "templates/microsoftfx"
        ],
    }
    ```
    
## Acknowledgement
Many thanks to [Steffen Wilke](https://github.com/steffen-wilke) and [Mickael Bonfill](https://github.com/jbltx) from whom I borrowed several source assets from their DocFX templates.
