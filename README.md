# My Presets Repository
Welcome to `YOUR REPO NAME` presets repository!

## How to add this repository to Gradience
In Gradience, open Presets Manager, and navigate to Repositories tab, click `+` button, and add requested information inside 'Add an custom repository' dialog.

## How can I add my preset to this repo?
Fork and clone this repository ([instructions](https://docs.github.com/en/get-started/quickstart/fork-a-repo)), add your preset to `presets/` directory, and update [`presets.json`](presets.json) file as shown below:

> **Note**
> Remember to write `name` value inside preset file in PascalCase with spaces, and filename in slug-case (known also as kebab-case) ([examples of this naming conventions](https://en.wikipedia.org/wiki/Naming_convention_(programming)#Examples_of_multiple-word_identifier_formats)).

```
{
    ...
    "My Awesome Preset": "https://github.com/User/ThisRepo/raw/main/presets/my-awesome-preset.json",
    ...
}
```
Create a PR to this repository to get your preset merged ([instructions](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)).

## Instructions for custom repository creators
Check out [Template.md](Template.md) for instructions on how to set up your custom repository on Github.

## License
<p>
<img src="https://www.gnu.org/graphics/gplv3-with-text-136x68.png" alt="GPLv3 logo" align="right">
This repository is licensed under the terms of the GNU GPLv3 license. You can find a copy of the license in the LICENSE file.
</p>
