# Atto
An Atomic Flexbox CSS Framework.

**Atto**: A unit prefix in the metric system denoting one trillionth.

+ Currently 2.4 KB [minified](http://www.minifier.org/).
+ Works in conjunction with [Tachyons.css](http://tachyons.io/), no class name conflicts.
+ Everything has been auto-prefixed for excellent cross-browser support.

#### Naming Conventions

##### Flex Container

|Shorthand	|Description|
|---|---|
|flex	|`display: flex`|
|row	|`flex-direction: row`|
|col	|`flex-direction: column`|
|wrap	|` flex-wrap: wrap`|
|mx	|justify-content (main axis)|
|cx	|align-items (cross axis)|
|ac	|align-content |

##### Flex Items

|Shorthand	|Description|
|---|---|
|c	| align-self|
|m	| justify-self (uses auto margin)|
|0 - 5	| order |

WIP: grow, shrink, and basis are on the way.

##### Alignment

|Shorthand	|Description|
|---|---|
|s	| start|
|c	| centre|
|e	| end|
|f	| stretch (fill)|
|b	| between |
|a	| around|

##### Examples

```
class='flex mxc' => .container {
  display: flex;
  justify-content: center;
}

class='flex col mxs cxc' => .container {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
}

class='ce 1' => .item {
  display: flex;
  order: 1;
}```
