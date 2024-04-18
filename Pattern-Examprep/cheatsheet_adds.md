- What each thing in the table for regression means
- Probability calcuation from regression -> done
- maximum margin linear decision boundary -> I get it
- Multiple R-Squared -> SSR / SST = sum(yn -t)^2 / sum(tn - t)^2
- number of parameters calculation -> done
- Why cross entropy rather than SE -> done
- In a Transformer architecture, a self-attention head is responsible for capturing dependencies between all words in the input sequence, regardless of their positions. It does this by assigning different attention scores to different words. The attention score determines how much focus to put on each word when encoding the current word. This mechanism allows the model to consider the entire context of the input sequence when generating the output.

Having multiple self-attention heads in a single Transformer block is beneficial for a couple of reasons:

Diverse Feature Capturing: Each self-attention head can potentially learn to focus on different types of relationships or patterns in the data. For example, one head might learn to pay attention to syntactic relationships between words (like subject-verb agreement), while another might learn to capture semantic relationships (like word synonymy). This diversity allows the model to capture a richer set of features from the data.
Increased Capacity: More self-attention heads increase the capacity of the model without significantly increasing the computational complexity. This is because the computations for each head can be done in parallel.
So, in summary, self-attention heads play a crucial role in capturing various dependencies in the input data, and having multiple heads allows the model to capture a more diverse set of features and increases the model’s capacity.

n a standard RNN-based encoder-decoder architecture, the context c is the final hidden state of the encoder. This context is a summary or an encoding of the entire input sequence. It’s used as the initial hidden state of the decoder and is designed to capture all the information in the input sequence necessary for the decoder to generate the correct output sequence.

However, there’s a limitation to this approach. The context c is of fixed size regardless of the length of the input sequence. This means it can be challenging for the encoder to compress all the necessary information, especially for long sequences, into this fixed-size context vector.