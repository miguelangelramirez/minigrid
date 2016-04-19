- [GitHub](https://github.com/henriquea/minigrid)
- [npm](https://www.npmjs.com/package/minigrid)

# Minigrid

Minimal 2kb zero dependency cascading grid layout without pain.

## Usage

It works on a grid container with a group of grid items.

```
<div class="cards">
  <div class="card"></div>
  <div class="card"></div>
  <div class="card"></div>
</div>
```

Then:

```
var grid = new Minigrid({
  container: '.cards',
  item: '.card',
  gutter: 6
});
grid.mount();
```

## Installation

Get it from <strong>npm</strong>.

```
npm install minigrid
```

Or 1998 script include tag from **npmcdn**.

```
npm install minigrid
```

## Upgrade

Upgrading from v1.x or v2.x?

Please read the [CHANGELOG](https://github.com/henriquea/minigrid/blob/master/CHANGELOG.md) for API changes.

## Limitations

Minigrid was built having in mind "cards" with same width and different heights. If your cards have different width sizes or you need more power I’d recommend [Isotope](http://isotope.metafizzy.co/).

- **Minigrid** v3.0.0
- [GitHub](https://github.com/henriquea/minigrid)
- [npm](https://www.npmjs.com/package/minigrid)
- [@healves82](https://twitter.com/healves82)