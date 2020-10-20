# BETA dictionaries for LifeCycle, Athlete and Longitools
The beta dictionaries are used to be able to initiate creation of dictonaries in the harmonisation process of new variables in a very early stage. As a PI you can manage and create new dictionaries which can be uploaded and tested by involved cohorts in a pilot phase of the project. Dictionaries can be changed and updated at any time and the network will be unaffected. After testing and approving the final beta dictionary the variables will be included in the main dictionaries and released when in the 3 months cycle.

## How it works
You need to have a few prerequisites
- [Git](https://git-scm.com/)
- [RStudio](https://rstudio.com/)
- [Opal](https://)
- [Excel](https://www.microsoft.com/nl-nl/microsoft-365/excel)

## Working with ds-beta-dictionaries
You need to 'clone' the repository on your own workingstation to be able to create new dictionaries. This means you get a copy of the directory on your own system. You can do this by executing the following command:

`git clone https://github.com/lifecycle-project/ds-beta-dictionaries`

Now you have your own copy to work in.

## Create dictionaries
Within the *dictionaries*-directory of the repository you need to create a dictionary for your study. This will 
result in a structure like:

- ds-beta-dictionaries
  - dictionaries
    - yourstudy
      - dict_#flavor$
      - dict_#different flavor$

The flavors can be:
- non_rep
- weekly_rep (0-)
- monthly_rep (0-219)
- trimester (1-3)
- yearly_rep (0-17)

Then you need to create a dictionary based upon the variables you want to harmonise. To illustrate how you do this you can use the [example](https://github.com/lifecycle-project/ds-beta-dictionaries/example-dictionary/example-dictionary-non_rep.xlsx) as a reference.

When you finished writing the dictionary you need to commit and push them to the repository on Github. Please check the [git-workflow](https://github.com/lifecycle-project/analysis-tutorials/blob/master/GIT-WORKFLOW.md) document to get the dictionaries exposed.

## Upload dictionaries and data to Opal
You can use the [dsUpload](https://lifecycle-project.github.io/ds-upload/) package to upload data and BETA dictionaries to Opal.

Check specifically the article [beta-dictionaries]().




