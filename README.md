# jasperserver
A docker'ized' JasperReports Server, pdf-server


## documentation
- https://community.jaspersoft.com/documentation/tibco-jaspersoft-studio-user-guide/v60/getting-started-jaspersoft-studio 
- or -> https://web.archive.org/web/20220707132735/https://community.jaspersoft.com/documentation/tibco-jaspersoft-studio-user-guide/v60/getting-started-jaspersoft-studio 

### Simple example with cURL
Fetch the report called `FyndlappTest.pdf` in the directory `/reports/RCReports/`

```
curl -u <user>:<password> http:/193.10.57.100/jasperserver/rest_v2/reports/RCReports/FyndlappTest.pdf --output 2021-fyndlapp.pdf
``` 
replace ```<user>``` with your user and ```<password>``` with your password ...

