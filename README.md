# ARCERIpy
An Ipython notebook aide for Active Reading using CERI


This repo contains a Jupyter notebook that presents a form to help you read your scientific papers actively.
The form follows the CERI framework, where CERI stands for:
* Claim
* Evidence
* Reasoning
* Implications.

By answering the questions in the form, you force yourself to answer the most important questions that you need to understand what's in the paper. This information is saved to a database for easy recollection at a later time (i.e. when writing your own paper).

The form is currently designed for papers in the field of exoplanets or astronomy in general, but can in principle be adapted for any field.

### To get started:
1. Clone this repo.
1. Run the ARCERI notebook in the terminal as `jupyter notebook ARCERI.ipynb`
1. The notebook contains three cells:
    1. The first cell tells the notebook to auto-execute all cells upon launching the notebook. Because this constitutes a security risk, Jupyter requires that you set the notebook to *Trusted* before this cell can do its job.
    1. The main code that spawns the form, the buttons and handles the saving of output.
    1. This cell hides the source code, such that the form looks and feels like any ordinary webform.
1. After confirming that these cells indeed pose no security risk, set the notebook to `Trusted` and restart Jupyter and the kernel.
1. Now, the form should spawn automatically and the cells containing the source code should be hidden. You are now ready to start reading papers with CERI!
