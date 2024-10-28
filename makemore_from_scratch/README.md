# zero_to_hero_nn
Zero to Hero Series from [Andrej Karpath](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)
***
### Overview: Makemore Part 1
Going over a basic NLP problem using autoregression method (predicting next character based on previous character). Similar to micrograd, this covers the nuances of NLP.
***

### Video 2: Building Makemore
Lessons Learned:
- Covered 2 ways of NLP: Simple autoregression vs. predicting characters using NN
- Nuances of PyTorch
    - torch.tensor vs torch.Tensor
    - Broadcasting Rule + Matrix multiplication
    - One hot encoding for nominal data
- Different Metrics for Loss/Quality of the Model:
    - log likelihood as a loss function
    - Using SoftMax as probability of the outputs

Summary: Makemore showcases the application of NN in natural language data. The video covered the nuances of PyTorch and other ways of measuring the quality (loss function) of the data + outputs (Softmax).