# Presets Repository Template
Use this repository as a template for creating a custom presets repository used in Gradience.

## How to use it
Go to the template's main page, and click a `Use this template` button, to generate a new repository on your account.
You can also clone this template, modify it, and put it as a new repository later.

## How to add presets to your repository
Copy a preset file (should be saved with .json extension) directly into `presets/` directory, and add link leading to it in `presets.json` file located in repository root.

> **Note**
> Remember to write `name` value inside preset file in PascalCase with spaces, and filename in slug-case (known also as kebab-case) ([examples of this naming conventions](https://en.wikipedia.org/wiki/Naming_convention_(programming)#Examples_of_multiple-word_identifier_formats)).

You can also put presets in different directories, or even store them on your own server. Just modify `presets.json` file and include a name of the preset, and a link redirecting to a file.

#### Example:
```json
{
    "My Awesome Preset": "https://github.com/You/YourRepo/raw/main/amazing_presets/my-awesome-preset.json",
    "Great Preset": "https://website.com/great-preset.json"
}
```

## How to add your repository to Gradience
In Gradience, open Presets Manager, and navigate to Repositories tab, click `+` button, and add requested information inside 'Add an custom repository' dialog.

## What you should change before publishing your repository?
There are some things you would like to change before making your repository public.

### Update README.md to include correct informations
Most notably, you would probably want to change title and `YOUR REPO NAME` placeholder, to a name of your repository.
<br>You should also update information in ***How can I add my preset to this repo?*** section, like presets directory and a link in the example code (You would want to only change `User` and `ThisRepo` values, and maybe `presets` if you changed presets directory name).

### Remove `preset-example` from repository
Remove `preset-example.json` preset file and its entry in `presets.json`, as they are intended only to showcase example structure of a preset repository.
