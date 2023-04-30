[![nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.jupyter.org/github/low-voltage-loadforecasting/book-case-study/blob/main/Case_Study_LV_Load_Forecasting_with_ML.ipynb) 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/low-voltage-loadforecasting/book-case-study/HEAD?labpath=https%3A%2F%2Fgithub.com%2Flow-voltage-loadforecasting%2Fbook-case-study%2Fblob%2Fmain%2FCase_Study_LV_Load_Forecasting_with_ML.ipynb)

[![Colab](https://img.shields.io/badge/open-in%20Colab-blue.svg)](https://colab.research.google.com/github/low-voltage-loadforecasting/book-case-study/blob/main/Case_Study_LV_Load_Forecasting_with_ML.ipynb) 

# Case Study Load Forecasting

## About

This Jupyter notebook accompanies the book Core Concepts and Methods in Load Forecasting, which is available here (TODO).

If you want to view it, you can open the .ipyn file directly, but it will be more nicely formatted if you view it with nbviewer. If you want to run it, read the next section.

If you want to use this tutorial, please attribute this repository. Where appropriate, you may also wish to cite our book: 
```
@book{Haben2023,
  title={Core Concepts and Methods in Load Forecasting: With Applications in Distribution Networks},
  author={Haben, Stephen, and Voss, Marcus, and Holderbaum, William},
  year={2023},
  publisher={Springer}
}
```

## How to run this case study?

You can run it locally on your computer, which gives you the most flexibility if you want to tinker with it. However, this may require you to install some Python libraries. Or you can run it on the free services Binder or Google Collab. We describe all these options below. 

### Running the Notebook Locally

To run the notebook on your local machine, follow these steps:

1. Clone this Github repository to your local machine by running the following command:

   ```
   git clone https://github.com/low-voltage-loadforecasting/book-case-study.git
   ```

2. Navigate to the directory where the notebook is located by running the following command:

   ```
   cd book-case-study
   ```

3. Install the necessary libraries using either `pip` or `conda`, depending on your preference. See the next section for instructions on how to do this.

4. Launch Jupyter Notebook by running the following command:

   ```
   jupyter notebook
   ```

5. In your web browser, navigate to `http://localhost:8888` to access the Jupyter Notebook dashboard.

6. Click on the notebook file to open it and start running the cells.

### Installing the Necessary Libraries

To install the necessary libraries for running the notebook, you can use either `pip` or `conda`.

#### Using Pip

1. Open a terminal or command prompt.

2. Navigate to the directory where the `requirements.txt` file is located by running the following command:

   ```
   cd book-case-study
   ```

3. Run the following command to install the necessary libraries using `pip`:

   ```
   pip install -r requirements.txt
   ```

   This will install all the necessary libraries listed in the `requirements.txt` file.

#### Using Conda

1. Open a terminal or command prompt.

2. Navigate to the directory where the `environment.yml` file is located by running the following command:

   ```
   cd book-case-study
   ```

3. Run the following command to create a new conda environment with the necessary libraries:

   ```
   conda env create -f environment.yml
   ```

   This will create a new conda environment named `lvbook` with all the necessary libraries installed.

4. Activate the new conda environment by running the following command:

   ```
   conda activate lvbook
   ```


### Run on Binder

Running the Notebook on Binder
To run the notebook on Binder, follow these steps:

Click on the "Launch Binder" badge in your repository to launch the notebook in a Binder environment.

Wait for the Binder environment to load. This may take a few minutes.

Once the environment has loaded, you should see the Jupyter Notebook interface.

Run the necessary libraries installation cell in the notebook to install the libraries required for the notebook. You can do this by clicking on the cell and then clicking on the "Run" button in the toolbar.

Once the libraries are installed, you can run the rest of the notebook and experiment with the code.

Note that the necessary libraries will be installed in a Binder environment by running the requirements.txt or environment.yml file that you previously created.



### Run on Google Colab

To run the notebook on Google Colab, follow these steps:

Click on the "Open in Colab" badge in your repository to open the notebook in Google Colab.

In the Colab toolbar, click on "Runtime" and then "Run all" to run all the cells in the notebook.

If prompted, click on "Connect to hosted runtime" to connect to a virtual machine that will run the notebook.

The necessary libraries should already be pre-installed in Google Colab, so you don't need to do anything else.

You can now run the notebook and experiment with the code.


## Frequently Asked Questions (FAQ)

Q: Can I use this repository to teach a class or incorporate it into a curriculum?

A: Yes! The repository is licensed under CC-BY, which allows for reuse and adaptation of the work for any purpose, including commercial uses and educational uses such as in a classroom setting. However, you must give proper attribution to the original work, including the author and repository link, and indicate any changes made to the work.

Q: Can I use this repository for commercial purposes?

A: Yes! The repository is licensed under CC-BY, which allows for commercial use of the work as long as proper attribution is given to the original work, including the author and repository link, and any changes made to the work are indicated.

Q: Can I make modifications to the code in the repository and use it in my own project?

A: Yes! The repository is licensed under CC-BY, which allows for modification and adaptation of the work for any purpose. However, you must give proper attribution to the original work, including the author and repository link, and indicate any changes made to the work.

Q: Do I need to ask for permission before using this repository?

A: No, permission is not required to use the repository as long as proper attribution is given to the original work, including the author and repository link, and any changes made to the work are indicated.

Q: Can I share this repository with others?

A: Yes! The repository is licensed under CC-BY, which allows for sharing and distribution of the work. However, you must give proper attribution to the original work, including the author and repository link, and indicate any changes made to the work.

Remember, it's important to always properly attribute any work you use or modify from this repository, and to indicate any changes made.