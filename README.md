# A Simplified GPT Implementation

A cleaned up the implementation of GPT model based on Karpathy's lectures.
This implementaiton can serve as the base for further refinements and related concepts.

Structure:
- Implementation of Causal Self Attention
- Stacking Self Attention machanisms to form Multi-Head Attention
- Adding point-wise feed-forward layers, skip connections, and layer normalizations to from the attention block
- Adding the Language Model head to generate predictions
- Trained as a simple character-level Language Model
