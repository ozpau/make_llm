# Attention


## Concrete

1.  What made modelling long sequences hard with RNN?
2.  In simplified attention, how do we compute context vectors for each
    token?
3.  How does attention help with modelling long sequences? What are the
    downsides and how are they accounted for?
4.  How do we extend simplified attention to allow for trainable
    weights?
5.  What kind of attention mask do text-generating LLMs use? Is it
    possible to use other masks? Why would we do that and what the
    implications would be?
6.  What is `register_buffer` used for?
7.  Is softmax necessary? What role does it play?
8.  How many context vectors do we need to compute?
9.  What are the different ways of implementing multi-head attention?
10. Why do we need multi-head attention and what can multi-head
    attention encode that larger single-head attention can’t encode?
11. When implementing multi-head attention, what are the tensor
    operations that we need to do and why?

## Extra questions

1.  Why do we need to divide by the square root of the dimension of
    key/value embedding in softmax?
2.  Is output projection layer necessary?
3.  Why do you need dropout? When and where dropout is typically
    applied?

## More Abstract

1.  How hard is it to change context length of a model?
2.  What are the implications of using dot-product when computing
    attention weights? Are there any alternatives and what would change
    if they were used?
3.  How can you go about interpreting attention weights?
4.  What are some of the things one can try to reduce amount of
    computation required to compute context vectors?
5.  How does attention in LLM differ from human attention?
6.  Is attention limited to text?

## Redundant

1.  How does attention mechanism help maintain contextual relevance over
    long passages of text?
