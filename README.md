
Anti Money Laundering (AML)

Money laundering is the process used to disguise the source of money or assets derived from criminal activity. Money laundering involves approximately 590 USD billion to 1.5 trillion USD per year worldwide. In 2018, 46.7 billion USD was laundered through Canada with 7.4 billion USD accounted in British Columbia. Canadian real state is a prime target for money laundering. For banks, it is important to comply the legislation from FINTRAC and OSFI.

from IPython.display import Image
from IPython.core.display import HTML
Image(filename = "aml.png", width=800, height=800)

For the sake of the task, it is important to reduce the false positive alarms while having very low tolerance to false negatives. False negatives, are critical because they may be problematic for the bank in terms of legislation and affect the reputation of the bank. It is important to analyze the context of the transactions/users relationships to improve effectiveness of the alarms.
Description of the dataset

The Elliptic Dataset (Kaggle: https://www.kaggle.com/datasets/ellipticco/elliptic-data-set) is a graph network of Bitcoin transactions with handcrafted features. All features are constructed using only publicly available information. This anonymized data set is a transaction graph collected from the Bitcoin blockchain.The Elliptic DataSet maps Bitcoin transactions to real entities in two categories:

- Licit: exchanges, wallet providers, miners, licit services, etc.
- Ilicit: scams, malware, terrorist, organization, ransomware, Ponzi shcemes, etc.

The task on the dataset is to classify the illicit and licit nodes in the graph. A given transaction is licit if the entity that generated it was licit.

Credit: M. Weber, G. Domeniconi, J. Chen, D. K. I. Weidele, C. Bellei, T. Robinson, C. E. Leiserson, "Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics", KDD ’19 Workshop on Anomaly Detection in Finance, August 2019, Anchorage, AK, USA.
