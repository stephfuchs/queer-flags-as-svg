# Pride Flags (LGBTQIA+ Community) as SVG plus ally flag

[![GitHub license](https://img.shields.io/github/languages/top/stephfuchs/queer-flags-as-svg?style=for-the-badge)](https://github.com/stephfuchs/queer-flags-as-svg)
[![GitHub release version](https://img.shields.io/github/v/release/stephfuchs/queer-flags-as-svg?&style=for-the-badge)](https://github.com/stephfuchs/queer-flags-as-svg/releases)
[![GitHub release date](https://img.shields.io/github/release-date/stephfuchs/queer-flags-as-svg?style=for-the-badge)](https://github.com/stephfuchs/queer-flags-as-svg/releases)
[![GitHub license](https://img.shields.io/github/license/stephfuchs/queer-flags-as-svg?style=for-the-badge)](https://github.com/stephfuchs/queer-flags-as-svg/blob/main/LICENSE)

This repository includes the SVG data for queer flags. As extra there will also be the straight ally flag and the
straight flag.

## SVG Viewbox calculation

The `viewbox` of each flag is calculated by its stripe count and the height of a stripe. In general is the height of
each stripe set to `1000px`. The origin is always set to `x=0.0` and `y=0.0`

```text
viewboxHeight = stripeCount * 1000px
viewboxWidth = viewboxHeight + 2000px
xPosStripe = 0
yPosStripe = viewboxHeight - 1000
widthStripe = 100%
heightStripe = 1000px
```

### Overview for calculated values for stripes

Table for the `x` and `y` position of a single stripe.

stripe position | x position | y position
--- | --- | ---
#1 | 0 | 0
#2 | 0 | 1000
#3 | 0 | 2000
#4 | 0 | 3000
#5 | 0 | 4000
#6 | 0 | 5000
#7 | 0 | 6000
#8 | 0 | 7000
#9 | 0 | 8000
#10 | 0 | 9000

Table for the flag `width` and `height` by given stripe count.

stripe count (on flag) | flag width (in px) | flag height (in px)
--- | --- | --- | 
1 | 3000 | 1000
2 | 4000 | 2000
3 | 5000 | 3000
4 | 6000 | 4000
5 | 7000 | 5000
6 | 8000 | 6000
7 | 9000 | 7000
8 | 10000 | 8000
8 | 11000 | 9000
8 | 12000 | 10000

### Example for 5 stripes

```svg

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7000 5000">
    <rect fill="#000000" width="100%" height="1000" y="0" x="0"/>
    <rect fill="#A9A8A8" width="100%" height="1000" y="1000" x="0"/>
    <rect fill="#FFFFFF" width="100%" height="1000" y="2000" x="0"/>
    <rect fill="#AACE79" width="100%" height="1000" y="3000" x="0"/>
    <rect fill="#FFFFFF" width="100%" height="1000" y="4000" x="0"/>
</svg>
```

## Pride flag color overview

The following tables containing all used colors (incl. their hex value) for the pride flags. Most of the are used in
other flags as well. It's an alphabetic order.

### A-Gender

hex-value | color
---       | ---
`#000000` | ![#000000](https://via.placeholder.com/50x20/000000/000000?text=+)
`#A9A8A8` | ![#A9A8A8](https://via.placeholder.com/50x20/A9A8A8/000000?text=+)
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#AACE79` | ![#AACE79](https://via.placeholder.com/50x20/AACE79/000000?text=+)
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#A9A8A8` | ![#A9A8A8](https://via.placeholder.com/50x20/A9A8A8/000000?text=+)
`#000000` | ![#000000](https://via.placeholder.com/50x20/000000/000000?text=+)

### A-Romantic

hex-value | color
---       | ---
`#3DA543` | ![#3DA543](https://via.placeholder.com/50x20/3DA543/000000?text=+)
`#AACE79` | ![#AACE79](https://via.placeholder.com/50x20/AACE79/000000?text=+)
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#A9A8A8` | ![#A9A8A8](https://via.placeholder.com/50x20/A9A8A8/000000?text=+)
`#000000` | ![#000000](https://via.placeholder.com/50x20/000000/000000?text=+)

### A-Sexuality

hex-value | color
---       | ---
`#000000` | ![#000000](https://via.placeholder.com/50x20/000000/000000?text=+)
`#808080` | ![#808080](https://via.placeholder.com/50x20/808080/000000?text=+)
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#730099` | ![#730099](https://via.placeholder.com/50x20/730099/000000?text=+)

### Bi

hex-value | color
---       | ---
`#D60270` | ![#D60270](https://via.placeholder.com/50x20/D60270/000000?text=+)
`#9B4F96` | ![#9B4F96](https://via.placeholder.com/50x20/9B4F96/000000?text=+)
`#0038A8` | ![#0038A8](https://via.placeholder.com/50x20/0038A8/000000?text=+)

### Demisexual

hex-value | color
---       | ---
`#000000` | ![#000000](https://via.placeholder.com/50x20/000000/000000?text=+)
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#730099` | ![#730099](https://via.placeholder.com/50x20/730099/000000?text=+)
`#808080` | ![#808080](https://via.placeholder.com/50x20/808080/000000?text=+)

### Gay

hex-value | color
---       | ---
`#3d1a78` | ![#3d1a78](https://via.placeholder.com/50x20/3d1a78/000000?text=+)
`#7bade2` | ![7bade2](https://via.placeholder.com/50x20/7bade2/000000?text=+)
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#98e8c1` | ![#98e8c1](https://via.placeholder.com/50x20/98e8c1/000000?text=+)
`#078e70` | ![#078e70](https://via.placeholder.com/50x20/078e70/000000?text=+)

### Genderfluid

hex-value | color
---       | ---
`#ff66b3` | ![#ff66b3](https://via.placeholder.com/50x20/ff66b3/000000?text=+)
`#FFFFFF` | ![FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#6E2381` | ![#6E2381](https://via.placeholder.com/50x20/6E2381/000000?text=+)
`#000000` | ![#000000](https://via.placeholder.com/50x20/000000/000000?text=+)
`#2E57A4` | ![#2E57A4](https://via.placeholder.com/50x20/2E57A4/000000?text=+)

### Genderqueer

hex-value | color
---       | ---
`#A37EB6` | ![#A37EB6](https://via.placeholder.com/50x20/A37EB6/000000?text=+)
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#4C8331` | ![#4C8331](https://via.placeholder.com/50x20/4C8331/000000?text=+)

### Inter

hex-value | color
---       | ---
`#ffcc00` | ![#ffcc00](https://via.placeholder.com/50x20/ffcc00/000000?text=+)
`#730099` | ![730099](https://via.placeholder.com/50x20/730099/000000?text=+)

### Lesbian

hex-value | color
---       | ---
`#e62e00` | ![#e62e00](https://via.placeholder.com/50x20/e62e00/000000?text=+)
`#ff8533` | ![#ff8533](https://via.placeholder.com/50x20/ff8533/000000?text=+)
`#FFFFFF` | ![FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#ff66b3` | ![#ff66b3](https://via.placeholder.com/50x20/ff66b3/000000?text=+)
`#b30086` | ![#b30086](https://via.placeholder.com/50x20/b30086/000000?text=+)

### Non-Binary

hex-value | color
---       | ---
`#ffcc00` | ![#ffcc00](https://via.placeholder.com/50x20/ffcc00/000000?text=+)
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#730099` | ![#730099](https://via.placeholder.com/50x20/730099/000000?text=+)
`#000000` | ![#000000](https://via.placeholder.com/50x20/000000/000000?text=+)

### Pan

hex-value | color
---       | ---
`#ff33cc` | ![#ff33cc](https://via.placeholder.com/50x20/ff33cc/000000?text=+)
`#ffcc00` | ![#ffcc00](https://via.placeholder.com/50x20/ffcc00/000000?text=+)
`#3399ff` | ![#3399ff](https://via.placeholder.com/50x20/3399ff/000000?text=+)

### Poly-Sexuality

hex-value | color
---       | ---
`#730099` | ![#730099](https://via.placeholder.com/50x20/730099/000000?text=+)
`#028137` | ![#028137](https://via.placeholder.com/50x20/028137/000000?text=+)
`#2E57A4` | ![#2E57A4](https://via.placeholder.com/50x20/2E57A4/000000?text=+)

### Trans

hex-value | color
---       | ---
`#3399ff` | ![#3399ff](https://via.placeholder.com/50x20/74D7EE/000000?text=+)
`#FFAFC8` | ![#FFAFC8](https://via.placeholder.com/50x20/FFAFC8/000000?text=+)
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#FFAFC8` | ![#FFAFC8](https://via.placeholder.com/50x20/FFAFC8/000000?text=+)
`#74D7EE` | ![#74D7EE](https://via.placeholder.com/50x20/74D7EE/000000?text=+)

### special pride flags

This is a list of flags which represent the queer community

#### Rainbow flag (1979)

hex-value | color
---       | ---
`#E30613` | ![#E30613](https://via.placeholder.com/50x20/E30613/000000?text=+)
`#F18815` | ![#F18815](https://via.placeholder.com/50x20/F18815/000000?text=+)
`#FFED00` | ![#FFED00](https://via.placeholder.com/50x20/FFED00/000000?text=+)
`#028137` | ![#028137](https://via.placeholder.com/50x20/028137/000000?text=+)
`#2E57A4` | ![#2E57A4](https://via.placeholder.com/50x20/2E57A4/000000?text=+)
`#6E2381` | ![#6E2381](https://via.placeholder.com/50x20/6E2381/000000?text=+)

#### Rainbow flag (Philadelphia People Of Color Inclusive, 2017)

hex-value | color
---       | ---
`#000000` | ![#000000](https://via.placeholder.com/50x20/000000/000000?text=+)
`#613915` | ![#613915](https://via.placeholder.com/50x20/613915/000000?text=+)
`#E30613` | ![#E30613](https://via.placeholder.com/50x20/E30613/000000?text=+)
`#F18815` | ![#F18815](https://via.placeholder.com/50x20/F18815/000000?text=+)
`#FFED00` | ![#FFED00](https://via.placeholder.com/50x20/FFED00/000000?text=+)
`#028137` | ![#028137](https://via.placeholder.com/50x20/028137/000000?text=+)
`#2E57A4` | ![#2E57A4](https://via.placeholder.com/50x20/2E57A4/000000?text=+)
`#6E2381` | ![#6E2381](https://via.placeholder.com/50x20/6E2381/000000?text=+)

#### Rainbow flag (progress pride flag, 2018)

hex-value | color
---       | ---
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#FFAFC8` | ![#FFAFC8](https://via.placeholder.com/50x20/FFAFC8/000000?text=+)
`#74D7EE` | ![#74D7EE](https://via.placeholder.com/50x20/74D7EE/000000?text=+)
`#613915` | ![#613915](https://via.placeholder.com/50x20/613915/000000?text=+)
`#000000` | ![#000000](https://via.placeholder.com/50x20/000000/000000?text=+)
`#E30613` | ![#E30613](https://via.placeholder.com/50x20/E30613/000000?text=+)
`#F18815` | ![#F18815](https://via.placeholder.com/50x20/F18815/000000?text=+)
`#FFED00` | ![#FFED00](https://via.placeholder.com/50x20/FFED00/000000?text=+)
`#028137` | ![#028137](https://via.placeholder.com/50x20/028137/000000?text=+)
`#2E57A4` | ![#2E57A4](https://via.placeholder.com/50x20/2E57A4/000000?text=+)
`#6E2381` | ![#6E2381](https://via.placeholder.com/50x20/6E2381/000000?text=+)

#### Ally flag (also known as _straight allys_)

hex-value | color
---       | ---
`#000000` | ![#000000](https://via.placeholder.com/50x20/000000/000000?text=+)
`#FFFFFF` | ![#FFFFFF](https://via.placeholder.com/50x20/FFFFFF/000000?text=+)
`#E30613` | ![#E30613](https://via.placeholder.com/50x20/E30613/000000?text=+)
`#F18815` | ![#F18815](https://via.placeholder.com/50x20/F18815/000000?text=+)
`#FFED00` | ![#FFED00](https://via.placeholder.com/50x20/FFED00/000000?text=+)
`#028137` | ![#028137](https://via.placeholder.com/50x20/028137/000000?text=+)
`#2E57A4` | ![#2E57A4](https://via.placeholder.com/50x20/2E57A4/000000?text=+)
`#6E2381` | ![#6E2381](https://via.placeholder.com/50x20/6E2381/000000?text=+)

## Issue tracker

Missing a flag? Wrong color? Other bugs found or having any questions? Please feel free to add a ticket
in [`Issues`](https://github.com/stephfuchs/queer-flags-as-svg/issues).

## License

MIT License

Copyright (c) 2021 Stephfuchs

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
documentation files (the "Software"), to deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit
persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the
Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

