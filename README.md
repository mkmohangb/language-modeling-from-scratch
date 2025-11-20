## language-modeling-from-scratch
  - Follow the stanford [course](https://stanford-cs336.github.io/spring2025/)


### Lecture 1
  - How to train the best model given a fixed set of resources?
  - Design decisions
    - basics
      - tokenization
      - architecture
      - loss function
      - optimizer
      - learning rate
    - systems
    - scaling laws
    - data
    - alignment
   
- Tokenziation
  - convert between strings and sequences of integers(tokens)
  - Byte-Pair encoding (BPE) Tokenizer
- Architecture
  - Variants:
    - Activation functions: ReLU, SwiGLU
    - Positional encodings: sinusoidal, RoPE
    - Normalization: LayerNorm, RMSNorm
    - Placement of normalization: pre-norm vs post-norm
    - MLP: dense, mixture of experts
    - Attention: full, sliding window, linear
    - lower-dimensional attention: group-query attention (GQA), multi-head latent attention(MLA)
    - state-space models: Hyena
- Training
  - Optimizer (e.g. AdamW, Muon, SOAP)
  - Learning rate schedule (e.g. cosine, wsd)
  - Batch size (e.g. critical batch size)
  - Regularization (e.g. dropout, weight decay)
  - Hyperparameters (number of heads, hidden dimension): grid search   

  
