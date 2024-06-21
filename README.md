# Text Summarization using Pegasus and T5 on BBC News Summary Dataset

This project demonstrates text summarization using Pegasus and T5 models on the BBC News Summary dataset. Below are instructions to run the provided Jupyter Notebook file (`text-summarization-v2.ipynb`) and details on the project's data analysis, visualization, and the rationale behind choosing Pegasus for fine-tuning.

## Instructions to Run the Notebook

### Prerequisites
- Python 3.x
- Jupyter Notebook
- PyTorch
- Transformers library by Hugging Face
- Datasets library by Hugging Face

### Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/NileshArnaiya/text-summarize-bbc-news.git
   

2. Install
    ```bash
    pip install torch torchvision transformers datasets


## Data Analysis

- The BBC News Summary dataset consists of news articles categorized into different topics such as business, entertainment, politics, sport, and tech.
- Statistical analysis includes examining the distribution of articles across topics, average article length, and summary length.

## Data Visualization

- Visualizations include bar plots for topic distribution and histograms for article and summary lengths.
- Scatter plots may be used to show relationships between article length and summary length.

## Thought Process Behind Choosing Pegasus

### Rationale

- **Pegasus Model:** Chosen for its strong performance in abstractive summarization tasks.
- **Pretrained Model:** Leverages transfer learning to fine-tune on a large corpus of data, capturing semantic nuances and language structure.
- **Comparison with T5:** Considered T5 for its versatility in text generation tasks, but Pegasus was preferred due to its specific design for summarization.
- **Fine-Tuning Strategy:** Adopted a fine-tuning approach to adapt the general summarization capabilities of Pegasus to the specific domain of BBC News articles.

