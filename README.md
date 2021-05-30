# AWS-CDK
Resource: https://docs.aws.amazon.com/cdk/latest/guide/home.html

1. mkdir aws-sample-cdk-constructs
2. cd aws-sample-cdk-constructs
3. create a cdk project using below commmand for typscript language
>>cdk init app --language typescript

Note : if you face any issues while intializing 

cdk.ps1 cannot be loaded because running scripts is disabled on this system. For more information,  
see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
At line:1 char:1
+ cdk init app --language typescript
+ ~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess

Solution please run this command to fix the issue: 
>>Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

4. To install dependencies 
>>npm i
