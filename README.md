## The New Broadleaf Commerce Demo Site

This Maven project is meant to be used as a solid started project for any [Broadleaf Commerce](http://www.broadleafcommerce.org) application. It has many sensible defaults set up along with examples of how a fully functioning eCommerce site based on Broadleaf might work.

One typical way of using this project would be to follow the [Getting Started Guide](http://docs.broadleafcommerce.org/current/Getting-Started.html), which would walk you through using our pre-bundled Eclipse workspace.

However, if you would like to utilize your own workspace or IDE configuration, you may prefer to fork this project. This would give you the added benefit of being able to pull in upstream changes as we work to improve the DemoSite.

> Note: If you are going to fork this project, we recommend basing your work on the `master` branch, and not the develop branch. develop is our ongoing development branch and there are no guarantees of stability on it.

-------
Ajay - 25 Sept 2013

This is the base project uploaded as is from the demosite git hub. stable branch 3.0. It is not the broadleaf project itself, but a template ecommerce app, that is constructed using Broadleaf libraries. 

Note the structure. There is a container Pom, which has core, site and admin. site is the customer facing project that creates one war (deployed at default 8080 and https version as well). the admin site is for internally facing ops for the content management, workflows and adminstration. 

to set this in eclipse, please follow the getting started instructions at http://docs.broadleafcommerce.org/core/current/getting-started . Just that instead of zip containing workspace, we start with downloading the project from git. 

Retain the master at the branch obtained from broadleaf, and create more branches for other changes. 