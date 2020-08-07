# SVG is turing-complete-ish: 
For SVG to be truly turing complete, it must have its output fed to it's input--- making this only a sort of driven turing machine.
\
Scalable Vector Graphics is an XML based language with significant image processing capabilities, and here I demonstrate that SVG can theoretically do arbitrarily large (but ultimately finite) computations.
\
It does so by unrolling a fixed number of iterations of [rule 110](http://mathworld.wolfram.com/Rule110.html), which IS turing complete, using SVG image filters.\
\
Runs in `Chromium 73.0.3683.103` after several seconds, seriously, this thing is slow!\
\
Behold the monstrocity in-browser [here](https://tom-p-reichel.github.io/svg-is-turing-complete/110.html).
\
Technical information found in the source, for those further interested.
