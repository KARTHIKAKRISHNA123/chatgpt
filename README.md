# GPT-2 Model in TensorFlow (From Scratch)

This is an implementation of GPT-2 using TensorFlow and Keras, inspired by the "Attention is All You Need" paper and OpenAI’s GPT-2 architecture.

## 🔧 Features
- Multi-Head Self-Attention
- Transformer Blocks
- Positional and Token Embeddings
- Output layer for language modeling

## 🛠️ How to Use
```bash
python GPT2.py

Model: "functional"
_________________________________________________________________
 Layer (type)                Output Shape              Param #
=================================================================
 input_layer (InputLayer)    [(None, 1024)]            0
 gpt2 (GPT2)                 (None, 1024, 50257)       163,087,441
=================================================================
Total params: 163,087,441 (622.13 MB)
Trainable params: 163,087,441 (622.13 MB)
Non-trainable params: 0 (0.00 B)


## 📎 Model Specs

| Feature                     | Value                     |
|----------------------------|---------------------------|
| **Input Sequence Length**  | 1024 tokens               |
| **Vocabulary Size**        | 50,257 tokens             |
| **Embedding Dimension**    | 768                       |
| **Number of Transformer Layers** | 12                 |
| **Attention Heads**        | 12                        |
| **Feed Forward Dimension** | 3072                      |
| **Dropout Rate**           | 0.1                       |
| **Activation Function**    | GELU                      |
| **Total Parameters**       | 163,087,441               |
| **Trainable Parameters**   | 163,087,441               |
| **Non-trainable Parameters** | 0                      |

