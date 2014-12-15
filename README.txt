2014/12/15
Jan van Oorschot

This stand-alone version of the Grails grails-email-confirmation plugin 
was created to accomodate the latest version of grails.

THis version is not stored in one of the global Grails/Maven repositories,
and it needs to be installed in the local Maven repository.
Do this as follows:

	grail compile
	grails maven-install
	
When installed localy, it can be used by adding the following line
in BuildConfig.groovy

	compile ":email-confirmation:3.0.0"
	
	