# EPID639_00_Base_Project
 

This repository installs packages that are relevant for the class: EPID 639 "R for Epidemiologic Data Analysis". This project should be established in Posit Cloud as a "template project" so that subsequent projects will have the relevant packages installed.

The first step is to make this project and install the package, set the access to all workspace members, in the special access section check the “Make this project a template” box. When a project has been designated as a template, it will appear in the New Project from Template dialog. It will no longer appear in the All Content list, but will be shown in the special Templates list and tagged as a template. You can update a template’s name, description and image in the Project Settings: Info panel.
In the special access section also check the “Make it the RStudio / Jupyter default” box to make it the default template for future projects.
Key resource: 
https://docs.posit.co/cloud/guide/projects/#project-templates

Remember to increase the allocation for this project in Posit Cloud under the gear icon. The default is 0.5Gb. With this level, I was unable to compile package RcppEigen, a dependency of ggpubr. I was successful with 4Gb allocation.

In a future iteration, you can crosscheck and delete the unfiled packages against later class projects. 

## Try to change the global options

Tools --> Global options --> Code --> Display --> Rainbow parentheses
Tools --> Global options --> ? Unable to figure out how to change the defaul quarto markdown from visual editor to source editor.


## Files and descriptions:

EPID639_00_Base_Project.Rproj  This is the R project directory containing relevant files.

Install_packages.qmd  This is the quarto markdown file containing the code to install relevant packages for the course.

## Instructions:

1.  Prior to each semester, run the code in the "Install_packages.qmd" file.

2.  Update the project settings in Posit so that the access is open to everyone in the class.

3.  Then in the class workspace, set this project as the "base project". Whenever you install a new project, remember to set this as the base project.
