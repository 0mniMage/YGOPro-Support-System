For each language there needs to be an offline, and online translation file. On startup after settings are applied the system will translate itself from English by going over a `JSON` file that corrosponds to each language. Conditional loading will need to be changed to run the translation files once. The identifier with be a `data-translation` HTML attribute value.

```JavaScript
var languageCode = {
    'identifier' : 'translation',
    'in'         : 'translation',
    'English'    : 'translation
}