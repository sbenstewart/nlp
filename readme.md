# Ingredient by Extraction and Identification

A system that automatically classifies the recipe (example French, Italian, etc.. ) and Extracts the Ingredients used in it .

### This is a NLP project by @sbenstewart and @SivaK18

# Dependencies

 * Jupyter Notebook - Anaconda Environment - https://www.anaconda.com/distribution/
 * Python packages - a pip install with all names below will do good
    * pandas
    * numpy
    * sklearn
    * bokeh
    * re , base64 , pdb
    * matploylib.pyplot
    * collections

# How to work

Once dependencies are installed open the code.ipynb file in jupyter and run the kernel

#### Project is in two halves

* Identification part
  * This is identify the recipe and categorize them according to their cuisine (Bayesian classification, empirical evaluation, bokeh model, Linear Regression)
  * recipe is the input and cuisine is output

* Ingredient extraction part - this has 2 parts
  * first part is identifying the main part of the ingredient (pepper, flour etc..) (Peter Norvig's method)
  * second part is to extract additional info about the ingredient used . This is done by assigning weights to the words near to the ingredient identified (sort of a n - gram problem ) and identifying the adjunct (noun describer) that is used in the sentence (NLU).



###### Have a nice day :)
