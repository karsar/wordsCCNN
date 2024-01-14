# README

## Overview
This repository contains resources for replicating computational experiments with combinatorial CNNs and other architectures focusing on word classification.

## Usage Instructions

### Setting Up the Environment

1. **Datasets**: 
   - For palindrome-related experiments, download and extract `palindromes.zip` from [this link](https://osf.io/qfhcy/?view_only=dc5b9d0639c74849a19a5da750531452). 
   - Download and extract `passwords.zip` from the same link for password-related experiments.
    
Both zip files contain precomputed combinatorics obtained by executing GeneratePalindromes.ipynb, GenerateNonPalindromes.ipynb and GeneratePasswords.ipynb.

### Running Experiments

1. **Palindrome Experiments**:
   - To generate palindromes, use `GeneratePalindromes.ipynb`.
   - To generate non-palindromes, use `GenerateNonPalindromes.ipynb`.
   - For (combinatorial) CCNN-based experiments, use `palindromeCCNN.ipynb`.
   - For CNN-based experiments, use `CNN_palindrome.ipynb`.
   - For LSTM-based experiments, use `LSTM_RNN_palindrome.ipynb`.
   - For GRU-based experiments, use `GRU_RNN_palindrome.ipynb`.
   - For Transformer experiments, use `Transformer_palindrome.ipynb`.

2. **Password Experiments**:
   - To generate passwords, use `GeneratePasswords.ipynb`.
   - For (combinatorial) CCNN-based experiments, use `passwordsCCNN.ipynb`.
   - For CNN-based experiments, use `CNN_passwords.ipynb`.
   - For LSTM-based experiments, use `LSTM_RNN_passwords.ipynb`.
   - For GRU-based experiments, use `GRU_RNN_passwords.ipynb`.
   - For Transformer experiments, use `Transformer_passwords.ipynb`.

### Additional Resources
- Full lists of palindromes, non-palindromes, strong (good) and weak (bad) passwords are available in corresponding `.txt` files within the datasets.

## License
This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
