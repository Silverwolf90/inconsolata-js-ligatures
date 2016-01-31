# Inconsolata + JavaScript Ligatures

This is the font **Inconsolata** with some ligatures mostly useful for people writing JavaScript. There are a few other modifications in addition to the ligatures. All the ligatures were originally taken from [Fira Code](https://github.com/tonsky/FiraCode) although I made some slight modifications.

I've never used FontForge before and I kind of stumbled through the program, so it's  more than likely I didn't do stuff according to best practices but it seems to work (on Windows 7 in Atom, untested anywhere else).

### Ligatures

* `===` Strict equal
* `!==` Strict not equal
* `=>` Arrow Functions
* `<=` Less than or equal to
* `>=` Greater than or equal to
* `||` Or
* `&&` And

#### Before

![](http://i.imgur.com/nyAmVYe.png)

#### After

![](http://i.imgur.com/rWO3vz9.png?1)

This is a bit opinionated, as I never use `==` and `!=` so I have the strict versions only take up 2 characters instead of 3.

### Other Modifications

* Single and Double quotes are now straight - used the glyphs in [Inconsolata-dz](http://nodnod.net/2009/feb/12/adding-straight-single-and-double-quotes-inconsola/)

### Usage in Atom

The editor Atom supports ligatures through the following:

```css
atom-text-editor {
  font-family: 'Inconsolata', 'Courier New', Courier;
  text-rendering: optimizeLegibility;
}
```
