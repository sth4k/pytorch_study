# pytorch_study
journey learning pytorch

## tutorial material
https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials

## FAQ
### RNN
1. pack_padded_sequence and pad_packed_sequence in LSTM

Basically they are to save the computation cost when you use RNN structure for variable lengths. similar to tensorflow dynamic_rnn

example here https://github.com/HarshTrivedi/packing-unpacking-pytorch-minimal-tutorial

explained here https://stackoverflow.com/questions/51030782/why-do-we-pack-the-sequences-in-pytorch
