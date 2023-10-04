# DVMIB
Deep Variational Multivariate Information Bottleneck

This github repository includes an implementation of the DVSIB method as described in the paper: "Deep Variational Multivariate Information Bottleneck - A Framework for Variational Losses."

**Authors:** 
- Eslam Abdelaleem ([Email](mailto:eslam.abdelaleem@emory.edu))
- K. Michael Martini ([Email](mailto:karl.michael.martini@emory.edu))

**License:** 
- [MIT License](link-to-license-file)

**Version History:**
- **v1.0 (6 October 2023):** Initial release.

**Dependencies:**
- Python
- PyTorch
- NumPy
- Matplotlib
- Scikit-learn

## Usage Instructions:

1. Execute the cells in DVMIB-DVSIB-For Github.ipynb notebook sequentially.
2. The notebook uses a custom Noisy MNIST dataset (details in the paper). Generate the data by executing the DVMIB-Data Generation.ipynb notebook.
3. The first section loads and preprocesses the dataset, including splitting it into training, validation, and test sets, and visualizing the data.
4. The second section defines the DVSIB model, performs training, and visualizes the embeddings using t-SNE.
5. The third section assesses the quality of classifications using Linear SVM and Neural Networks.

For questions, issues, or support, please visit our [Issue Tracker](link-to-issues) or contact us via email.

Happy experimenting with DVSIB!
