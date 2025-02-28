# Interesting Things I Learned During This Projects. 

  - Let's explore from beginning

  - # Token Generating Techniques
    ### Byte-Pair Encoding (BPE):-
      - a compression algorithm used in Natural Language Processing (NLP) to represent large vocabulary with a small set of subword units.
      - Introduced by Rico Sennrich and team in 2016.
      - Widely used in Machnine Translation, machine translation, text classification, and text generation.
    ### SentencePiece :-
      - SentencePiece is a unsupervised text tokenizer and detokenizer primarily used for Neural Network-based text generation tasks.
      - In SentencePiece two technique is used first is Byte-Pair Encoding and Unigram Language Model.
    DeepSeek uses Hugging Face 'tokenizer' library.

  - # Bigram Language Model:-
      - In this project, I used a bigram model to create embeddings from scratch.
      - The Bigram Language Model predicts the next word based on the current word.

        ![image](https://github.com/user-attachments/assets/bdff843b-b365-43d7-9c17-1fb9a82164d5)


# Training of Bigram Model:
  - The model uses an nn.Embedding layer to map each character to a dense vector (embedding).
  - These embeddings are learned during training and capture the relationships between characters.
  - #### Optimizer:
    - Adam: Adam optimizer (short for Adaptive Moment Estimation) combines the benefits of two other optimization techniques: Momentum and RMSprop. It is widely used.
    - Validation loss for 100 epoch.
     ![image](https://github.com/user-attachments/assets/e4079d9e-415c-42cc-8ec0-3292edb0e7d1)
