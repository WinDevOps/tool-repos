# TL;DR current tool-summary

Pester - Powershell BDD testing (like rspec)

chocolatey - Package Mgmt System based on nuget

dropkick - Fluent based deployment

msysgit - Git 

nuget - like ruby gems for windows

posh-git - git prompt for powershell

psget - powershell module management

roundhouse - version control for a SQL db

uppercut - build system


# tool-repos
==========

This repository serves as a best of breed toolkit that aligns with "windows devops".  I started this repo, on github in particular, to raise awareness within the MS Windows community.  I have discussed with many MSFT employees the "git force", and determined they are either blind to a culture outside of their own ecosystem (TFS, Visual Studio, System Center, yadayada) or just deny its existence as part of a marketing strategy.  I consider this denial or ignorance to be one of the biggest risks to the longevity of their platforms.  Ultimately failure to embrace it will steer developers, sysadmins, and operators  alike to platforms that do.  Lets set things straight, contribute, and show them where it's at.  

One final note- this is not meant to be a codeplex redux.  This is meant to focus on tooling that facilitates topics such as :
Version Control, Continuous Integration, Built Pipelines, Bug Tracking, Integrated Testing, Automated Deployment, etc.

The format for structure should be as follows:

	top-level repo -
			project_name -
				      README.md (review/information)
				      git submodule to repo (if appropriate)

Please do not put any actual code in here.


## Example

Adding a repo:

	mkdir project_name
	git submodule add https://github.com/username/project_name project_name/repo
	echo "[link](http://github.com/username/project_name)" > project_name/README.md
	git add project_name
	git commit -am 'added project_name'
