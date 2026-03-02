# Character-Level Text Generation using GRU

A deep learning project that generates text using a character-level Recurrent Neural Network (GRU) implemented in PyTorch.



## Problem Statement

Generating coherent text sequences is a fundamental task in Natural Language Processing.  
This project builds a character-level language model using a Gated Recurrent Unit (GRU) network to learn sequential dependencies and generate new text.



## Model Architecture

- Embedding Layer
- GRU (Gated Recurrent Unit)
- Fully Connected Output Layer
- CrossEntropy Loss
- Adam Optimizer

The model learns character-by-character patterns from input text data.



##  Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib
- Jupyter Notebook



## How to Run

1. Clone the repository:

2. Install dependencies:

    pip install -r requirements.txt

3. Run:
    jupyter notebook text-generation-gru.ipynb  



##  Project Structure



│── text-generation-GRU.ipynb
│── requirements.txt
│── README.md


## Future Improvements

- Add LSTM comparison
- Implement temperature sampling
- Use larger dataset
- Add validation loss tracking
- Convert notebook to modular Python scripts


## Training Details

- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Model Type: GRU-based RNN
- Task: Character-level language modeling


## Example Output

Input Seed:
"Once upon a time"

Generated Text:
"Once upon a time there was a kingdom..."
