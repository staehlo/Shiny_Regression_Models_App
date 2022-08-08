# Shiny_Regression_Models_App

This is a training project that explores the functionality of R's Shiny Apps. The application lets users enter two series of data and then select either a linear or a non-linear regression model. The app will compute the equation and give out a table of goodness of fit measures. Finally, the app also displays the result in the form of an interactive plotly graph that also shows the confidence and prediction intervals.

The app can be viewed at [rahace.shinyapps.io/regression_models](https://rahace.shinyapps.io/regression_models/)

Further information on Shiny apps:  
[cran.r-project.org/web/packages/shiny](https://cran.r-project.org/web/packages/shiny/)  
[shiny.rstudio.com](https://shiny.rstudio.com/)

<img style="width:60%; height:auto;" src="https://github.com/staehlo/Shiny_Regression_Models_App/blob/main/screenshot_for_readme.png" alt="Screenshot of Shiny App">

## Technology

The app was build with R version 4.2.1 using RStudio 2022.07.0 Build 548.

The following packages - and versions - were used:

* ggplot2 - 3.3.6
* investr - 1.4.2
* plotly - 4.10.0
* shiny - 1.7.2
* shinythemes - 1.2.0

## How to download and run it locally

(absolute beginner's guide)

You need to have R, and git installed. RStudio is not necessary but helpful.

1\. Open a Linux terminal or Windows command line shell and go to the folder where you wish to download the application to.

2.\ Install the necessary R packages from within the R console. For example, if you are missing ggplot2, you can enter:  
`install.packages('ggplot2')`

3.\ Clone the repository to your computer by entering in your Linux terminal or Windows command line:  
`git clone https://github.com/staehlo/shiny_regression_models_app` 

Now you have two possibilites:

A\. Launch the Shiny App via the command line:  
4\. Change the working directory to the *shiny_regression_models_app* folger by typing:  
`cd shiny_regression_models_app`

5\. Start R from the command line by simple entering `R`.

6\. In the R console, type `library("shiny")`  

7\. In the R concole, type `runApp("regression_models")`

8\. The app should automatically start in your default web browser.

B\. Launch from within RStudio:  
4\. In the top menu go to 'File' -> 'Open File' and select the 'app.R' file from the Shiny App.

5\. Click on the 'Run App' button in the top right corner above the script.

6\. The app should start in RStudio's 'Viewer' panel.
