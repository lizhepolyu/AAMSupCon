# AAMSupCon

# Proposed Architecture

![The proposed architecture leverages additive angular margin loss and supervised contrastive learning.](./aamsupcon.pdf)

The proposed architecture leverages additive angular margin loss and supervised contrastive learning. The encoder transforms the acoustic features (MFCC or FBank) to low-dimensional normalized embedding vectors. Invariance occurs for the embeddings (e.g., **z₁** and **ẑ₁**) whose acoustic features (**x₁** and **ẋ₁**) come from the same speaker. On the other hand, embeddings (e.g., **z₁** and **z₂**) whose acoustic features (**x₁** and **x₂**) belong to different speakers are far apart. The blue boxes represent the projection network. See text for details.

