# Translation of MindBox display language

> Our [official website address](https://www.mindbox.cc), you can learn more about the content of the inspiration box on the official website
> 

## Add a new language

First look for `Locale Identifier: zh`(take `zh` as an example) in your country or region in the `locale-identifiers.json` file. See if there is already a folder named `zh` in the `locales` folder, if not, create a folder with `zh` and copy the files in the `en` folder into the `zh` folder, translating the field values from the `translation.json` file into the language of your country or region. Note that during translation, the `{{count}}` text is retained.

## Improve translations for existing languages

Since the MindBox is constantly iterating, so some new text will be added, so the existing translations are likely to be outdated, when you find outdated or missing translations in the process of using the MindBox, we are very welcome to modify or add new translations, in the `locales/en` folder of the `translation.json` file, you can find all the text that needs to be translated, of course, the syntax in this file will also have errors, welcome to correct

## Thanks

- English by [Jocs](https://github.com/Jocs)
- Simplified Chinese by [Jocs](https://github.com/Jocs)