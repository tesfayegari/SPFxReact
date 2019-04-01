## sp-fx-react

This is a React webpart that creates nice form. 
To use this webpart please create a list called 	Employee Registration with the following columns:
Title	Single line of text	
Description	Single line of text	
Projects	Managed Metadata (You need to have a managed data Country with terms of countries)	
Department	Choice	(Human Resource,Finance,Employee) - (When Employee is selected ExternalHiring is turned off by default)
ExternalHiring	Yes/No	
ReportingManager	Person or Group	


### Building the code

```bash
git clone the repo
npm i
npm i -g gulp
gulp
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options


