# Sandpiles
Some simulations of 1D and 2D sandpiles in Mathematica along with a project poster presenting results. 

### Simple explanation of what I did:
My simulations gave me weird results that did not look like the results from the original papers on sandpiles. I discovered that this was because my formulation for the toppling rules was slightly different. After gathering some data and investigating this further with different toppling processes, I found that avalanche size seems to follow power-law distributions regardless of whether or not toppling rules contained dependence on neighboring cells. However, it also looks like avalanche length does not exhibit this invariance. This is weird, because this is not at all what we would expect.

# Poster
I made a poster to present my results. Here is a link to the poster:
https://github.com/apanana/Sandpiles/blob/master/Poster/main.pdf

The following are excerpts from that poster.

### Abstract 
In the following, I will introduce the sandpile model and the closely-related phenomenon of self-organized criticality. I present my own simulations of some 1D and 2D sandpile configurations and discuss the results. The focus of these simulations was to investigate the presence of power laws in 2D sandpiles with varied toppling processes. Simulation results suggest that the power laws exhibited by avalanche size are invariant to dependence on neighboring states in the toppling process. 

### Conclusion

Though it is tempting to say SOC in general is invariant to the toppling process, that is not necessarily the case. Though invariance was observed for $P(s)$, it was found that in the ``Sloped'' configuration, plots of the avalanche length no longer exhibit power laws.
It is also noted that the toppling process does affect the range of possible avalanche sizes, even if power laws were still observed. A question that remains unanswered is whether this behavior is true for all toppling rules or if the ones I used were simply lucky picks.
Further work could be done on either a closer examination of other SOC features affected by toppling behavior, or an investigation into the effects of other topplings rules on avalanche size.
