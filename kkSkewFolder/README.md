# SkewFolder

A third-order skew and wave folding effect. 

This Sound consists of three stages of skewing and three stages of wave folding. The Structure parameter allows you to smoothly change the arrangement of these stages between three different orderings: 

- pre-skew where all the skewing stages act on the Input signal first before it is folded;
- interlaced where each skew stage is followed by a fold stage;
- and post-skew where the signal is folded first then skewed. 

The FoldScheme parameter lets you smoothly change between simultaneous and sequential schemes. In the sequential scheme, as Fold increases, the folding level of each stage is increased in turn. Only when a stage has reached its maximum level of folding will the subsequent stage start to fold. 

In the simultaneous scheme all folding stages are increased together. 