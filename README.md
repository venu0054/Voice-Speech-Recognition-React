# react-speech
A simple react component to deal with browser SpeechRecognition

## Getting started
Install the module via npm.
```
npm install react-speech
```
Than import the script and the style to your project:
```js
import ReactSpeech from 'react-speech';
import 'react-speech/build/css/index.css'
```
Now you can use the __react-speech__ component everywhere in your application:
```jsx
<ReactSpeech onText={(t) => console.log(t)} />
```
For more informations about the SpeechRecognition API visit the [official](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition) page.

## Props
* __lang__: The language of the current SpeechRecognition. If not specified, this defaults to the HTML lang attribute value, or the user agent's language setting if that isn't set either.

## Events
* __onText__: Called when a word or phrase has been positively recognized and this has been communicated back to the app.

## Development
Clone the project repository, than install the dependencies and run:
```
npm run start
```
this will fire up the grunt development environment with a http server and actions on file changes, than when you have done your editing you can run:
```
npm run build
```
to package the project to be ready for production.

---

## License
The __react-speech__ is released under the MIT License by [codekraft-studio](https://codekraft-studio.github.io/).

## Contributing

1. Fork it ( https://github.com/codekraft-studio/react-speech/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
3. Write and run the tests (`npm run test`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
