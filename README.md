# Predicting-Next-Word-Using-LSTM

- I use the file which is **pride and prejudice** to predicting the next word. 
- I downloaded this file from the [project gutenberg](https://www.gutenberg.org/).
- After importing all library and file, I did preprocessing on the file data. I removed the unneccessary charcters.
- Using tokenizer, words are converted into tokens. Each word has unique token.
- For predicting the next word, i took the previous three words.
- I split the data into `X` and `y`. `X` means three tokens. `y` means fourth token.
- Applying one hot encoding on `y`.
- Building the LSTM model and predicting the next word.
