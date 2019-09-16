# Cool Disclaimer: 
For SVG to be truly turing complete in the sense of being able to run arbitrarily long tasks, it must have its output fed to it's input--- a sort of driven turing machine. However, this loop can be unrolled an arbitrary non-infinite length, so tasks of known maximum complexity can be computed in one go...\

With this out of the way and apologies for being misleading:\

# SVG Is Turing Complete
Scalable Vector Graphics is an XML based language with significant image processing capabilities, and here I demonstrate that these capabilities breach turing completeness.\
\
The turing machine I choose to emulate to prove SVG's turing completeness is [rule 110](http://mathworld.wolfram.com/Rule110.html).\
\
Runs in `Chromium 73.0.3683.103` after several seconds, seriously, this thing is slow!\
\
Behold the monstrocity in-browser [here](https://tom-p-reichel.github.io/svg-is-turing-complete/110.html).
\
Technical information found in the source, for those further interested.
