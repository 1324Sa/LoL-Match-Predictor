# League of Legends Match Predictor (PyTorch)

Final project for **Introduction to Neural Networks with PyTorch** (IBM, Coursera).

A logistic regression model built in PyTorch that predicts whether a League of Legends match ends in a **win** or a **loss**, using in-game statistics: kills, deaths, assists, gold earned, CS, wards placed, wards killed and damage dealt.

## What the notebook covers
| Task | Description |
|---|---|
| 1 | Load the dataset, split train/test (80/20), standardize, convert to tensors |
| 2 | Logistic regression model (`nn.Linear` + sigmoid), `BCELoss`, `SGD` |
| 3 | Training loop (1000 epochs) and train/test accuracy |
| 4 | L2 regularization (`weight_decay=0.01`) |
| 5 | Confusion matrix, classification report, ROC curve and AUC |
| 6 | Save and load the model with `torch.save` / `torch.load` |
| 7 | Hyperparameter tuning of the learning rate (0.01, 0.05, 0.1) |
| 8 | Feature importance from the model weights |

## How to run
```bash
pip install -r requirements.txt
jupyter notebook LoL_Match_Predictor.ipynb
```
Then choose **Kernel → Restart & Run All**. The dataset downloads automatically from IBM's Cloud Object Storage.

## Files
- `LoL_Match_Predictor.ipynb`: the full project notebook with outputs
- `screenshots/`: one screenshot for each task
- `requirements.txt`: Python libraries

## Author
Saleh Khaled Saleh Alzhrani
