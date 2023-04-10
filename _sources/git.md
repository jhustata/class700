# git

It's a Stata class but the world has moved on from pure statistical computing to a more involved process beginning with the conception of a project, its successful management, and ultimately publication!

Stata has not made the full transition as have other more nimble open-source platforms such as Python and R. As such Stata is an outstanding, user-friendly, and commercially-available platform for statistical computing. In this advanced class we'll push you to appreciate these virtues.

However, we also wish to make it clear to you that the needs of a graduate, academic, and industry expert beyond 2020 are very dynamic, emerging, and heavily based on an online self-publishing platform such as this class book!

Your goal over the next 5 weeks is to collaborate as one team on a single project, with technical aspects to it as well as self-publishing demands. We will guide you on how to set yourselves up for online publishing using Python- and R-based platforms. But by week 6 you'll be able to replace much of your webcontent with .html material directly outputted by Stata!

The project you are going to collaborate on is inspired by a problem that arose in the 340.600 class in the second week. Your instructor shared a .dofile script that was meant to perform the following tasks:

1. imported .SAS files from the CDC website (.do file equivalents)
2. translate their content into Stata syntax and export the products as .do files
3. queue the .do files to construct the NHANES III survery with over 3700 variables from questionnaire, exam, lab
4. perform a mortality-linkage of these survey participants over a 30-year period from as early as 1988 through 2018.
5. set up the user for survival analysis using non-parametric (Kaplan-Meier), semi-parametric (Cox regression), and parametric (Weibull) approaches. And show-case the versatility of macros and Stata programs.

As it turns out, the vast majority of students have Stata/BE or IC, which cannot handle more than 2400 variables. But I've addressed this issue: https://jhustata.github.io/book/fff.html

When a user enters the following commands in succession:

```Stata
do https://raw.githubusercontent.com/jhustata/book/main/nhanes-alpha.ado

nhanes
```

The program automatically curates an NHANES III dataset with only the 27 variables they need for the specific class content if they are running Stata/BE or IC. Or it will curate the full NHANES III dataset with 3700+ variables if they are running Stata/SE or MP.

Your challange as one team is to make this program flexible enough to meet all sort of user-based-needs. Thus far the program only meets the needs for a specific Stata class session.

Not to worry, you are going to learn more about programming in each passing week. And with such a clear task at hand, you'll be alert to every new idea presented in class.

