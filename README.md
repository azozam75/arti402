# ARTI402 — Deep Learning Labs

Student ID: **2240006095**

Completed Jupyter notebooks for labs 2, 4, 5, 6, 7, 8, and 9. Each includes the exercise solutions, written checkpoint answers where requested, and saved execution outputs. All seven notebooks were executed from a fresh kernel and passed every supplied assertion. Existing lab 1 and lab 3 submissions are preserved.

| Lab | Topic | Completed notebook |
|---|---|---|
| 2 | Activations, loss, gradients, and backpropagation | [ARTI402_lab2_2240006095.ipynb](lab02/ARTI402_lab2_2240006095.ipynb) |
| 4 | RNN and LSTM architecture | [ARTI402_lab4_2240006095.ipynb](lab04/ARTI402_lab4_2240006095.ipynb) |
| 5 | SGD, momentum, RMSProp, and Adam | [ARTI402_lab5_2240006095.ipynb](lab05/ARTI402_lab5_2240006095.ipynb) |
| 6 | Regularization, initialization, and batch normalization | [ARTI402_lab6_2240006095.ipynb](lab06/ARTI402_lab6_2240006095.ipynb) |
| 7 | TensorFlow and Keras | [ARTI402_lab7_2240006095.ipynb](lab07/ARTI402_lab7_2240006095.ipynb) |
| 8 | PyTorch and explicit training loops | [ARTI402_lab8_2240006095.ipynb](lab08/ARTI402_lab8_2240006095.ipynb) |
| 9 | Autoencoders, representations, and denoising | [ARTI402_lab9_2240006095.ipynb](lab09/ARTI402_lab9_2240006095.ipynb) |

## Running a notebook

Install Python 3.13 and the packages in `requirements.txt`, then open the notebook in Jupyter and select **Restart Kernel and Run All Cells**. Run it from its lab folder. For labs 4–9, keep that folder's `arti402_figures.py` beside the notebook; the helpers differ between labs. Lab 7 also demonstrates saving and reloading `spiral_model.keras` and creates that file when run.

All datasets are generated in the notebook or bundled with scikit-learn; no external dataset downloads are required. Saved outputs let you review the results without retraining. Random seeds are set in the experiments; small numerical differences can occur with different hardware or package versions.

## Source material

Exercises, instructional text, and plotting helpers are from [hindalzahrani10/arti402](https://github.com/hindalzahrani10/arti402), source commit `b059df92315522bcaa231e5f72af277e3087f2c2`. The original instructional cells and checks are retained, with completed solutions. In lab 9, the checkpoint answers explain why changing the bottleneck alone does not guarantee zero reconstruction loss in the supplied architecture.

Framework references: [Keras training API](https://keras.io/api/models/model_training_apis/), [Keras early stopping](https://keras.io/api/callbacks/early_stopping/), and [PyTorch documentation](https://docs.pytorch.org/).
