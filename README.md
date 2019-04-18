# CharRNN
Train a Character-RNN to generate new names.

# How it works
The RNN is trained on a large dataset of baby names. For each name, we create 2 character tokens in hopes of predicting the next character. We can then generate entirely new names by "seeding" the name with a few starting characters and by choosing the length of the new name.
