# BETA dictionaries for LifeCycle, Athlete and Longitools

## How it works
You need to have a few prerequisites
- [Git](https://git-scm.com/)
- [RStudio](https://rstudio.com/)
- [Opal](https://)
- [Excel](https://www.microsoft.com/nl-nl/microsoft-365/excel)

## Get the ds-beta-dictionaries
YOu need to 'clone' the repository on your own workingstation to be able to create new dictionaries. This means you get a copy of the directory on your own system. You can do this by executing the following command:

`git clone https://github.com/lifecycle-project/ds-beta-dictionaries`

Now you have your own copy to work in.

Within the *dictionaries*-directory of the repository you need to create a dictionary for your study. This will result in a structure like:
## Create dictionaries

- ds-beta-dictionaries
  - dictionaries
    - yourstudy

Then you need to create a dictionary based upon the variables you want to harmonise. To illustrate how you do this you can use the [example](https://github.com/lifecycle-project/ds-beta-dictionaries/example-dictionary.xlsx) as a reference.

When you finished writing the dictionary you need to commit and push them to the repository on Github. Please check the [git-workflow](https://github.com/lifecycle-project/analysis-tutorials/blob/master/GIT-WORKFLOW.md) document to get the dictionaries exposed.

## Upload dictionaries and data to Opal
You can use the [dsUpload](https://lifecycle-project.github.io/ds-upload/) package to upload data and BETA dictionaries to Opal.

Check specifically the article [beta-dictionaries]().




