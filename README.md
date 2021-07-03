## Fonts
Two fonts were referenced in the style guide, but the design appears to only use one. So, I only used the one that has two weights appropriate for the design.

## Mobile Layout
I decided that using a larger image and horizontal _points_ with [Fluid Typography](https://www.smashingmagazine.com/2016/05/fluid-typography/) looks better on mobile than the vertical _points_ proposed by the mobile design spec. If this were a real project, I'd do both and present them to the client to decide.

I didn't use the `image-header-mobile.jpg` image provided. It had very little difference from `image-header-desktop.jpg` and the desired appearance was better achieved with `width: 100%; height: 100%; object-fit: cover;`.

## Purple
I implemented the purple colorization of the grayscale photo provided with [`mix-blend-mode`](https://developer.mozilla.org/en-US/docs/Web/CSS/mix-blend-mode) after [several](https://codepen.io/VAggrippino/pen/WNjemJB) failed [attempts](https://codepen.io/VAggrippino/pen/ZEKEZyB) at figuring out how to get the right color with combinations of CSS filters including [`sepia`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/sepia()) and [`hue-rotate`](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/hue-rotate()).

I didn't end up with exactly the same coloring as shown in the design file, but I like the way mine turned out better.