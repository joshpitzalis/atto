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

...and you get all of the flexbox and grid alignment properties as atomic class names.

##### Examples

```
If you want space things on either end in a navbar:

<nav class='flex jcb'>
  <child1/>
  <child2/>
</nav>

This would be the same as giving the parent a class .nav {
  display: flex;
  justify-content: space-between;
}


Say you want something dead center in a parent div:

<parentDiv class='grid x' >
  <child/>
</parentDiv>

This would be the same as giving the parent a class .parent {
  display: grid;
  place items: center center;
}
```
