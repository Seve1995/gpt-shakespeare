# GPT Shakespeare - Text Generation with a Transformer Language Model

This project demonstrates text generation using a Transformer-based language model inspired by the works of William Shakespeare. The model is trained on Shakespearean text and can generate text that resembles Shakespearean prose.

## Project Files

- `gpt-shakespeare.ipynb`: Jupyter Notebook containing a detailed walk-through of the project, including model implementation, training, and text generation.

- `input.txt`: Training data file containing a collection of Shakespearean text used to train the language model.

- `gptV{x}.py`: Python script containing the implementation of the Transformer-based language model used for text generation.

## Requirements

- Python 3.6+
- PyTorch
- Jupyter Notebook (for running the walk-through notebook)

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/gpt-shakespeare.git

2. Navigate to the project directory:
   ```bash
    cd gpt-shakespeare
   
3. Install the required Python packages:
   ```bash
   pip install torch jupyter

4. Open and run the Jupyter Notebook `gpt-shakespeare.ipynb` to explore the project. This notebook provides a step-by-step guide on how to train the model and generate Shakespearean text.

5. You can modify hyperparameters, such as batch size, block size, learning rate, and embedding dimensions, in the `model.py` script to experiment with different settings.

6. To generate text using the trained model, follow the instructions in the notebook.

## Acknowledgments

This project was implemented by following this [video tutorial](https://www.youtube.com/watch?v=kCc8FmEb1nY).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



