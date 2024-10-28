# zero_to_hero_nn
Zero to Hero Series from [Andrej Karpath](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)
***
### Overview: micrograd
Going over the concept of NN and its structure of: forwardpass -> backward grad -> update weight -> repeat
***

### Video 1: Building Micrograd
Lessons Learned:
- Learn the fundamental basics of neural net and the concepts.
    - Concept of Partial gradients
    - Creating a class of a neuron with grad of simple operations.
    - Creating a class of neural network with neuron class.
    - Using activation functions from: $w*x + b$ to get an output.
    - Understanding the concept backward + forward pass to adjust $w$ to 'learn' the data using gradient descents

Summary: Micrograd showcases how neural network **fundamentally** operates. Using the **gradients** (of all parameters) of the **output loss**, the **weights** of each neurons **adjusts** with each pass.