### terraform modules

- created a modules directory and populated it with the cloud infrastructure directories and files
- added the cloud provider file to the root module

![](images/modules1.png)

![](images/modules11.png)

![](images/providertf2.png)

- set up alb directory
- populated it with main.tf, outputs.tf, etc files

![](images/albtfvar3.png)

![](images/albvartf33.png)

![](images/alboutputstf333.png)

- created vpc directory and followed the same process above

![](images/vpcmaintf4.png)

![](images/vpcoutputstf4.png)

![](images/vpcvariabletf4.png)

- added vpc and alb scripts to the root module file

![](images/modulesmaintf5.png)

- asg creation and population

![](images/asgbastionnginx6.png)

![](images/asgwebserver66.png)

![](images/asgvariablestf66666.png)

- compute creation and population

![](images/computemaintf7.png)

![](images/computevariabletf77.png)

- efs creation and population

![](images/efstf8.png)

![](images/efsvariabletf88.png)

- rds creation and population

![](images/rdstf9.png)

![](images/rdsvariabletf99.png)

- security creation and population

![](images/securitymaintf10.png)

![](images/securityoutputstf101.png)

![](images/securitytf1010.png)

![](images/securitysgrule10101.png)

![](images/securityvariabletf101010.png)

![](images/rootmodulemaintf1010101.png)

 - edited root modules file to include s3 bucket conf script

 - edited providers.tf file

 ![](images/backends3bucket11.png)

 ![](images/providerstflocal11.png)

  - ran the terraform init, fmt, validate, plan and apply commands

   ![](images/terraforminitfmtvalidatefmt12.png)

  ![](images/terraformplan121.png)

  ![](images/terraformplan1212.png)

  ![](images/terraformapply13.png)

  ![](images/terraformapply131.png)