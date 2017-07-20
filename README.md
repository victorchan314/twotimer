# Two-Time-Pad Cracker

I created this project for my Stanford Cryptography class as an extra credit assignment. The program can determine the secret key of a stream cipher given at least two messages encoded with that key. It depends on XORs of the ciphertexts and the fact that the messages are created from alphanumeric characters and punctuation marks. Because of this, it does not perfectly crack the key with fewer messages; however, with enough ciphertexts, it can determine the key to a high accuracy.
