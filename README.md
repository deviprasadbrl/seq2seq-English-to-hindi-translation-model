# seq2seq-English-to-hindi-translation-model


# English → Hindi Neural Machine Translation

Implementation of the paper

**Sequence to Sequence Learning with Neural Networks**
(Ilya Sutskever et al., 2014)

## Architecture

- Encoder: 2-layer LSTM
- Decoder: 2-layer LSTM
- Hidden Size: 512
- Embedding Size: 256
- Dataset: IITB English-Hindi (50k sentence pairs)

## Results

Training Loss

Epoch 0 : 4.84
Epoch 1 : 2.78
Epoch 2 : 1.77

BLEU

0.01

reversed input: 

Epoch: 0 Loss: 4.4664
Epoch: 1 Loss: 1.7509
Epoch: 2 Loss: 0.6077
Evaluating BLEU Score...
Final BLEU Score: 0.05

## Observations

- Vanilla Seq2Seq struggles with translation quality.
- Decoder tends to generate common Hindi words.
- This reproduces one of the motivations for introducing attention mechanisms.
