# Atto
An Atomic Flexbox CSS Framework.

**Atto**: A unit prefix in the metric system denoting one trillionth.

+ Currently 877 bytes [minified](http://www.minifier.org/).
+ Works in conjunction with [Tachyons.css](http://tachyons.io/), no class name conflicts.

## Yet Another CSS Framework?

No, this one is just an extension of [Tachyons](http://tachyons.io/). Full credit goes to Tachyons. I am a huge fan and I use it a lot, I just found that the [flexbox module](https://github.com/tachyons-css/tachyons-flexbox) class names were verbose and hard to remember so I wanted to create my own. I also wanted something that forced me to use the 38 CSS 2.1 properties that work in all browsers, for when flexbox isn't an option. Lastly, I learned a bunch of HTML best practices from reading [Heydon Pickering's](https://twitter.com/heydonworks) “[Inclusive Front-End Design Patterns](https://www.smashingmagazine.com/inclusive-design-patterns/)” book that I wanted to incorporate into a html starter boilerplate.

In Progress...

- [x] Abbreviate classnames to smaller snippets.
- [ ] Add flex basis, grow and shrink.
- [ ] Add all CSS 2.1 properties for fallbacks.
- [ ] Add an accessible HTML starter template.
- [ ] Add an accessible colour palette.
- [ ] host on unpkg.

#### Fallback [CSS 2.1 properties](http://caniuse.com/#search=css) (well-supported subset)
These properties are supported in effectively all browsers (since IE6+, Firefox 2+, Chrome 1+ etc)

##### Includes the following:

+ background-color
+ background-image
+ background-position (2 params)
+ background-repeat (repeat | repeat-x | repeat-y | no-repeat)
+ border-collapse (collapse | separate)
+ border-color
+ border-spacing
+ border-style
+ bottom
+ color
+ clear (none | left | right | both)
+ display (none | inline | block | list-item)
+ float (none | left | right)
+ font-family
+ font-size
+ font-style (normal | italic | oblique)
+ font-variant (normal | small-caps)
+ font-weight
+ height
+ left
+ line-height
+ list-style
+ list-style-image
+ list-style-position
+ margin
+ overflow (visible | hidden | scroll | auto)
+ padding
+ position (static | relative | absolute)
+ right
+ text-align (left | right | center | justify)
+ text-decoration (none | underline | overline | line-through)
+ text-indent
+ text-transform (capitalize | uppercase | lowercase | none)
+ top
+ width
+ word-spacing
+ visibility (visible | hidden)
+ z-index
