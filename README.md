# jasperserver
A docker'ized' JasperReports Server, pdf-server

## About Jasper
- https://www.jaspersoft.com/ 

## Resources from Tibco

Documentation
1. https://community.jaspersoft.com/documentation/tibco-jaspersoft-studio-user-guide/v60/getting-started-jaspersoft-studio 
2. https://web.archive.org/web/20220707132735/https://community.jaspersoft.com/documentation/tibco-jaspersoft-studio-user-guide/v60/getting-started-jaspersoft-studio 

Video:
1. https://www.youtube.com/watch?v=yRLvJgz9Dxk 




## Fetching the report from our server
### A simple example using cURL
Fetch the report called `FyndlappTest.pdf` in the directory `/reports/RCReports/`

```
curl -u <user>:<password> http:/<ip>/jasperserver/rest_v2/reports/RCReports/FyndlappTest.pdf --output 2021-fyndlapp.pdf
``` 
replace ```<user>``` with your user and ```<password>``` with your password ...

# How to create Reports

## 'Jaspersoft Studio'
- https://community.jaspersoft.com/project/jaspersoft-studio 

### Download 'Jaspersoft Studio CE' 
- Download the Community Edition (CE)
- https://community.jaspersoft.com/community-download 

### Getting started with Jaspersoft Studio
- https://community.jaspersoft.com/wiki/getting-started-jaspersoft-studio 

### Introduction to Jaspersoft Studio
- https://community.jaspersoft.com/wiki/introduction-jaspersoft-studio 

### Designing a report
- https://community.jaspersoft.com/wiki/designing-report-jaspersoft-studio 


