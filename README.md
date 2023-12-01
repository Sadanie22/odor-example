# Machine Olfaction
Using a data-driven fingerprint, obtained by training a LLM on a small data set of molecules for structure-odor prediction


The Datar file, where each smiles gets transformed to a CLS fingerprint is too big for github (52mb) and needs to be trained the notebook provided

Datar access (without CLS)
url = 'https://raw.githubusercontent.com/pyrfume/pyrfume-data/main/leffingwell/leffingwell_data.csv'


data = pd.read_csv(url)


data = data[['smiles', 'odor_labels_filtered', 'labels_train/test']]
