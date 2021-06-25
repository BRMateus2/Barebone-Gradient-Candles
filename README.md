# Barebone-Gradient-Candles
Colored Candlestick exemplifying a gradient.

It was somewhat hard to find a good working example of DRAW_COLOR_CANDLES that was understandable, most of the comments were useless, and the documentation lacks to even specify the plot limitations (PLOT_COLOR_INDEXES being limited to 64 in length, [0; 63]) or which order the functions should be called.

I also had a hard time finding a working algorithm for moving a X color towards a Y color (I believe this is called Gradient?); this code contains a math function which returns a gradient from X towards Y and I would love to know if someone has a better way of doing that.
