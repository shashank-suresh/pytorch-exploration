# Links
https://docs.pytorch.org/tutorials/beginner/basics/data_tutorial.html
https://docs.pytorch.org/vision/stable/generated/torchvision.datasets.FashionMNIST.html#torchvision.datasets.FashionMNIST

# Datasets & DataLoaders
- `torch.utils.data.Dataset` stores the samples and their corresponding labels
- `torch.utils.data.DataLoader` wraps an iterable around the Dataset to enable easy access to the samples

The idea is to decouple dataset code from the model training code for increased readability and modularity.

