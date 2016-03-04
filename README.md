# fol
Coldplay's Flower of Life, in CSS.

[Preview here](https://rawgit.com/kenrick95/fol/master/index.html)

![Result](https://raw.githubusercontent.com/kenrick95/fol/master/result.png)

Compare it with [the album art](http://coldplay.com/release/a-head-full-of-dreams/).

Yeah, mine is not perfect.

## Technical details
- Each circle is a div, with `border-radius`
- All of them are positioned to the centre of page, and then transformed (using CSS `transform`, specifically: `translateX`, `translateY`, and `rotate`)
- `calc()` is heavily used as `box-sizing` cannot bound the divs to middle of border
- `border-image` (+`linear-gradient`) and `border-radius` does not work well together
