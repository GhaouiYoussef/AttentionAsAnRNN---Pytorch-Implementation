# AttentionAsAnRNN - Pytorch Implementation
## Implementation Overview

- Implementation of the block diagram for Attention’s RNN Cell of Fig. 2.
- The class to implement will derive from `torch.nn.Module` implementing the forward method.
- A non-iterative implementation of the cell as described by the following formula for computing O_N at Section 3.1.
- Generate some dummy input and compute the absolute and relative error between the iterative and non-iterative implementations.
- Export in ONNX both implementations.
