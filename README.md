# Module for transliteration of cyrillic text into latin under the rules of [ISO 9](https://en.wikipedia.org/wiki/ISO_9)

### Enable
to use at server side run:
```
nmp install transliterate-cyr-to-latin
```

to use in browser download this module refer to the file module/index.js using the src attribute in the script tag.


### Usage
The module exposes *transliterate* function which should be called with one parameter of the type String. The function returns an output of the type String with all cyrillic characters replaced
with latin characters. Example:

```javascript
transliterate('Строка на русском языке або текст українською мовою');
```

a method *.noConflict* is available on *transliterate* object. This method, when invoken, restores the namespace transliterate to the previous value, if any.

