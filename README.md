# model-gen

## Links

Transformer explanation - http://jalammar.github.io/illustrated-transformer/ \
Attention is All You Need - https://arxiv.org/pdf/1706.03762.pdf

Google PolyGen paper - https://arxiv.org/pdf/2002.10880.pdf \
Google PolyGen repo - https://github.com/deepmind/deepmind-research/tree/master/polygen \
PolyGen explanation - https://towardsdatascience.com/generating-3d-models-with-polygen-and-pytorch-4895f3f61a2e \

## Notes

### Tensorflow

1. Load dataset, split into training and testing sets.
2. Pre-process data. e.g. normalise data such that it is in the range 0 -> 1 etc.
3. Build model
4. Compile model
5. Train model, using training dataset
6. Evaluate accuracy, using testing dataset
