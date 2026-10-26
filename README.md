# Why the tipping point seems to move

Interactive companion to the microbiome–immune model with cumulative inflammatory memory.

**Live page:** https://moeinkh88.github.io/CODE_microbiome_immune_ODE/

The full model (m, i, h) is autonomous, so its saddle S is one fixed point in 3-D.
The saddle that moves is the saddle of the 2-D (m, i) landscape with memory frozen at the
subject's current h. Memory only adds a constant push η·Φ_h(h) to dm/dt and di/dt, so each
value of h gives a different landscape with its saddle somewhere else.

On the page you can change the loop strengths G_mi and G_h, the memory half-life, and the
starting point (m(0), i(0), h(0)), place a subject just above or below its tipping size, and
scrub through time.

