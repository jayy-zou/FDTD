# Nonlinear FDTD from Scratch

This project provides a one-dimensional nonlinear Finite-Difference Time-Domain (FDTD) method developed from scratch as a proof of concept. It serves to illustrate the basic principles and key outcomes associated with FDTD, focusing on topics like electric and absorbing boundary conditions, linear and Chi 2 dielectric responses. The notebook is designed to offer users a preliminary understanding of FDTD techniques, enabling them to grasp essential concepts and observe phenomena such as second harmonic generation. While not built for efficiency and robustness, this implementation aims to give a natural starting point for those new to the field, aiming to facilitate a deeper exploration of wave phenomena in nonlinear optical media.

## Getting Started

These instructions will guide you through the initial setup of the project, allowing you to run the Jupyter notebook and explore the nonlinear FDTD method implemented in it.

### Prerequisites

Before you begin, ensure you have Anaconda installed to manage your environments and packages. You can download it from [Anaconda's website](https://www.anaconda.com/products/distribution).

### Installation

Follow these steps to get your development environment running:

1. **Clone the repository**:
   Clone the project to your local machine using the following commands:

   git clone https://github.com/jayy-zou/FDTD.git
   cd FDTD

2. **Create and activate the Conda environment**:
   Use the `environment.yml` file to create an Anaconda environment that replicates the project's setup:

   conda env create -f environment.yml
   conda activate your_env_name

3. **Launch Jupyter Notebook**:
   Once the environment is active, start the Jupyter Notebook to access the project:

   jupyter notebook

   Navigate to the notebook file in the Jupyter interface that opens in your browser to start working with the code.

### Deactivating the Environment

When you are done working with the notebook, you can deactivate the virtual environment by running:

   conda deactivate

This will return you to your base terminal environment.
