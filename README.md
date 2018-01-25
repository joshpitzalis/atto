# Atto

An Atomic CSS Framework for Grid & Flexbox.

**Atto**: A unit prefix in the metric system denoting one trillionth.

* Currently 2.5 KB [minified](http://www.minifier.org/).
* Works in conjunction with [Tachyons.css](http://tachyons.io/), no class name conflicts.
* Everything has been auto-prefixed for excellent cross-browser support.

### Naming Conventions

| Shorthand | Description                                        |
| --------- | -------------------------------------------------- |
| grid      | `display: grid`                                    |
| flex      | `display: flex`                                    |
| row       | `flex-direction: row` or `grid-auto-flow: column;` |
| col       | `flex-direction: column` or `grid-auto-flow: row;` |
| wrap      | `flex-wrap: wrap`                                  |

Combine one of these...

| Shorthand | Description     |
| --------- | --------------- |
| jc...     | justify-content |
| ai...     | align-items     |
| as...     | align-self\*    |

...with one of these...

| Shorthand | Description      |
| --------- | ---------------- |
| ...s      | start\*          |
| ...c      | centre\*         |
| ...e      | end\*            |
| ...f      | stretch (fill)\* |
| ...b      | space-between    |
| ...a      | space-around     |
| ...v      | space-evenly     |

...and you get all of the flexbox qnd grid alignmnet properties as atomic class names.

##### Examples

````
class='grid jcc' => .container {
  display: grid;
  justify-content: center;
}

class='flex col jcs aic' => .container {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
}

class='grid x' => .item {
  display: grid;
  place items: center center;
}```
````
