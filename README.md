# EPID639_00_Base_Project
 

This repository installs packages that are relevant for the class: EPID 639 "R for Epidemiologic Data Analysis". This project should be established in Posit Cloud as a "base project" so that subsequent projects will have the relevant packages installed.

Remember to increase the allocation for this project in Posit Cloud under the gear icon. The default is 0.5Gb. With this level, I was unable to compile package RcppEigen, a dependency of ggpubr. I was successful with 4Gb allocation.

In a future iteration, you can crosscheck and delete the unfiled packages against later class projects. 

## Files and descriptions:

EPID639_00_Base_Project.Rproj  This is the R project directory containing relevant files.

Install_packages.qmd  This is the quarto markdown file containing the code to install relevant packages for the course.

## Instructions:

1.  Prior to each semester, run the code in the "Install_packages.qmd" file.

2.  Update the project settings in Posit so that the access is open to everyone in the class.

3.  Then in the class workspace, set this project as the "base project". Whenever you install a new project, remember to set this as the base project.
