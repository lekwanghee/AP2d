# AP2d

## <Attentive pooling with dilated conv2d >
* BPE (byte pair encoding) - We use the codes in https://github.com/rsennrich/subword-nmt
* W/o pre-trained embeddings
* 4 dilated (2-dimensional) convolutional layers
* Neural MF based scoring

## Ohter methods implemented
NOTE! We do not use cos similarity. Instead, we use "[Neural MF](https://dl.acm.org/citation.cfm?id=3052569)".
* "[AP CNN](https://arxiv.org/abs/1412.3555)"
* "[ABCNN](https://arxiv.org/pdf/1512.05193.pdf)" 

## Reference codes
* https://github.com/locuslab/TCN 

## Data reference
* WikiQA http://aka.ms/WikiQA
