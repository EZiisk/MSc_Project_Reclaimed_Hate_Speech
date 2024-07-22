# MSc_Project_Reclaimed_Hate_Speech
MSc Data Science and AI Dissertation Project focusing on Reclaimed Hate Speech in NLP

## Introduction

This repository contains 16 Jupyter Notebooks, all of which have the suffix "EZ". These Notebooks are presented in chronological order, following the project timeline, and were developed using Google Colab. Therefore, they require specific Colab dependencies to run successfully. Accompanying datasets in CSV format can be found in the Datasets folder.

NB: Some Notebooks have been re-run for verification purposes and so their output may differ slightly from metrics displayed in the final dissertation paper.

Fine tuned models can be found publicly on Huggingface -  EZiisk/EZ_finetune_Vidgen_model_RHS_Best and tokenizer EZiisk/EZ_finetune_Vidgen_model_RHS_Best_Tokenizer


## Colab Dependencies
Google Colab Notebooks often depend on certain packages and configurations that are pre-installed in the Colab environment. These may include, but are not limited to:
- Google Colab's specific Python version.
- Libraries such as TensorFlow, PyTorch, Pandas, NumPy, Matplotlib, and others that are set to specific versions.
- Google Drive integration for file storage and access.
- GPU/TPU integration for accelerated computations.

## Libraries and Dependencies

All other required libraries, including but not limited to `Captum` and `Transformers`, are installed directly within the relevant notebooks. Therefore, users should not have to manually install any additional libraries to run the code.

## Data Files
The data used in these Notebooks are stored in CSV files. The naming convention for these CSV files is `Notebook_x_y_z_filename.csv`, where `x, y, z` represents the Notebook number(s) the CSV file is intended for.

## Specific Notebook Notes

1. **Notebook 1**: This Notebook uses `snscrape` for data extraction. However, as of the time of uploading this Notebook, `snscrape` is no longer functional due to changes in the Twitter API. Users may need to find an alternative method for data extraction or use pre-existing data.

2. **Notebooks 8, 9, 10**: 
    - After installing the `accelerate` module, it is imperative to **restart** the Notebook for the training to commence successfully.
    - These Notebooks contain code that logs into the Huggingface hub and verifies account identity. For security reasons, users should **comment out** this code before running the Notebooks.

## Conclusion

Please ensure you are aware of the above specifics when working with the Notebooks in this repository. Always check for updated dependencies or libraries to ensure smooth operation. Feedback and contributions are always welcome!
