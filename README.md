# Data Drift

This project uses the CIFAR 10 dataset to demonstrate data drift detection and mitigation.

## Dataset

The dataset provided has sub-folders D1 to D4 where the data in each of the sub-folders may or may not contain a specific drift based on the test split of the CIFAR 10 dataset. Further, each sub-folder has two levels (L1 and L2) of drift present: minor or severe.

You can use the Train and Test labels instead of the labels.npy:

- Train labels: `train_labels.npy`
- Test labels: `test_labels.npy`

Move the `train_labels.npy` and `test_labels.npy` into the `CIFAR10/` directory (not `CIFAR10/CIFAR10/`).

## Setup

Make sure to have Python 3.11.9 installed. If you are on a Mac, start the venv with:

```bash
source python311_venv/bin/activate
```
Then install the `requirements.txt`

```bash
pip install -r requirements.txt
```

Open `data-drift.ipynb`
You can also open this file in Google Collaboratory (Make sure to install all the libraries in requirements.txt and change the data's directory path)

Run all the cells