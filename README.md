[![bower version](https://img.shields.io/bower/v/k-speech.svg)](https://libraries.io/bower/k-speech) 
[![open issues](https://img.shields.io/github/issues/k4ng%2Fk-speech.svg)](https://github.com/k4ng/k-speech/issues) 
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://github.com/k4ng/k-speech) 


# \<k-speech\>

a simple component "text to speech".

<!--
```
<custom-element-demo height="300">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="k-speech.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<k-speech auto-play 
    text    = "Hello, perkenalkan nama saya kang cahya. Maaf aku mah cuma newbie."
    volumer = "1"
    rate    = "1"
    pitch   = "1"
    lang    = "id-ID"></k-speech>
```


## How to install

### bower

```markdown
bower install --save k-speech
```


## Properties

Attribute | Description | Default Value
--------- | ----------- | -------------
text | for set text | This is a simple component text to speech
lang | for set language | english
volume | for set volume | 1
rate | for set rate | 1 
pitch | for set pitch | 1 
auto-play | for set auto play | false
debug-voice-support | to know the language support in browser. When it is set to "true", you can see the results in the [inspect element->console](https://github.com/k4ng/k-speech/blob/master/screen%20shot.JPG) | false


## Support

### Desktop

Feature | Chrome | Edge | Firefox (Gecko) | Internet Explorer | Opera | Safari (WebKit)
------- | ------ | ---- | --------------- | ----------------- | ----- | ---------------
Basic support | 33 | (Yes) | 49 (49) | No support | ? | 7

### Mobile

Feature | Android | Chrome | Edge | Firefox Mobile (Gecko) | Firefox OS | IE Phone | Opera Mobile | Safari Mobile
------- | ------- | ------ | ---- | ---------------------- | ---------- | -------- | ------------ | -------------
Basic support | (Yes) | (Yes) | (Yes) | No support | 2.0 | No support | No support | 7.1


## Change log

You can find a list of all changes for each release in the [change log](https://github.com/k4ng/k-speech/blob/master/CHANGELOG.md).


## Contributing

1. Fork it!
1. Create your feature branch: git checkout -b my-new-feature
1. Commit your changes: git commit -m 'Add some feature'
1. Push to the branch: git push origin my-new-feature
1. Submit a pull request :D


## License

[MIT License](https://github.com/dyazincahya/k-speech/blob/master/LICENSE) 
