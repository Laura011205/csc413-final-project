# Models

## Fine-tuned BERT

- `fine_tuned_bert_lr_1e-4`: BERT learning rate = 1e-4, final test accuracy = 0.8768
- `fine_tuned_bert_lr_2e-5`: BERT learning rate = 2e-5, final test accuracy = 0.9096
- `fine_tuned_bert_lr_5e-4`: BERT learning rate = 5e-4, final test accuracy = 0.4973
- `fine_tuned_bert_lr_5e-5_2048_encodings`: BERT learning rate = 5e-5, 2048 encodings, final test accuracy = 0.9016
- `fine_tuned_bert_lr_5e-5`: BERT learning rate = 5e-5, final test accuracy = 0.9072
- `fine_tuned_bert_lr_v1`: BERT (manual training implementation, use as reference only, did not continue with testing due to huge fluctuations in training loss)

## GloVE + LSTM
- `glove_lstm_v2`: GloVE + LSTM learning rate = 0.001, final test accuracy = 0.8746
- `glove_lstm_v3`: GloVE + LSTM learning rate = 0.005, final test accuracy = 0.8859
- `glove_lstm_v4`: GloVE + LSTM learning rate = 0.008, final test accuracy = 0.893