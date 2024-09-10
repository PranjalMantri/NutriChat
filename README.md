---

# NutriChat

**NutriChat** is a question-answer chatbot based on a large language model (LLM). It cab answer all your doubts related to nutrition. It is a RAG application written mainly using pytorch and utilises a local GPU to run the LLM.

## Dependencies

To run the NutriChat notebook, you need the following dependencies:

- Python 3.12+
- Jupyter Notebook or Jupyter Lab
- PyTorch (preferably compiled with CUDA for optimal performance)
  ```bash
  pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
  ```

## Installation

1.  Clone this repository to your local machine:
    ```bash
    git clone https://github.com/PranjalMantri/NutriChat.git`
    ```
2.  Install the required Python dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3.  Launch the Jupyter Notebook:

    ```bash
    jupyter notebook NutriChat.ipynb
    ```

- You can customize the list of queries by editing the `query_list` in the notebook.
