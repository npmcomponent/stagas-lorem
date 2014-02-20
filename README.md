*This repository is a mirror of the [component](http://component.io) module [stagas/lorem](http://github.com/stagas/lorem). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/stagas-lorem`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# lorem

text and image placeholders

## Install

`component-install stagas/lorem`

## API

### lorem(n:Number)

  Generate a lorem ipsum of word length `n`.

### lorem.p(n:Number)

  Generate a paragraph element
  of lorem ipsum of word length `n`.

### lorem.img(width:Number, height:Number, category:String, [index]:Number, [text]:String)

  Generate a lorem ipsum image.
  Returns an object with `el` and
  `url` properties.

## License

MIT
