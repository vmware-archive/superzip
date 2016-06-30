[Superzip Shiny Gallery example](https://github.com/rstudio/shiny-examples/tree/master/063-superzip-example), slightly modified to run on Cloud Foundry (CF).  If you have Pivotal VPN access, you can find a [live version of the app running on CF here](http://superzip.cfapps.pez.pivotal.io/).

Please refer to the [Shiny Apps on CF section](http://pivotalsoftware.github.io/gp-r/#shiny_cf) of the Pivotal & R Practitioner's Guide for guidance on how the original code from RStudio was slightly modified to run on CF.  In line with what is described in the guide, only the following files were modified/added from the original RStudio code to make this hapen:

* Modified: [ui.R](https://github.com/pivotalsoftware/superzip/blob/master/superzip/UI.R), [server.R](https://github.com/pivotalsoftware/superzip/blob/master/superzip/server.R)
* Added: [init.r](https://github.com/pivotalsoftware/superzip/blob/master/init.r), [startscript.R](https://github.com/pivotalsoftware/superzip/blob/master/startscript.R), [manifest.yml](https://github.com/pivotalsoftware/superzip/blob/master/manifest.yml)
