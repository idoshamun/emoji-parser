[![Build status](https://travis-ci.org/idoshamun/emoji-parser.svg?branch=master)](https://travis-ci.org/idoshamun/emoji-parser)

##&lt;emoji-parser&gt;

`<emoji-parser>` transforms a text with colons/unicode based emojis into a HTML which shows them.
For more information about the parsing and the parameter, please refer to [js-emoji](https://github.com/iamcal/js-emoji).


Example:

```html
<emoji-parser content="Hello World :grin:"></emoji-parser>
<emoji-parser content="Hello World &#x1F601;" method="unified"></emoji-parser>
```

### Styling
The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--emoji-size` | The emoji span size | `1.3em`
 

