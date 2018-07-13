# Data augmentation tool

# Run script
First, install required libraries:

```bash
pip install joblib textblob -U
```

Download the necessary NLTK corpora

```bash
python -m textblob.download_corpora
```

Run the script

```bash
python extend_dataset.py train.csv
```

In the end, there would be a new csv files in the extended_data directory.
