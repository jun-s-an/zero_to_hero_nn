# zero_to_hero_nn
Zero to Hero Series from [Andrej Karpath](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)
***
### Overview
From many forums and conversations with Data Scientists/MLEs, learning through his course of `zero to hero` helps you learn the overview of deep.
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