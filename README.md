# AzurePipeline4Flutter

Using Azure devops pipeline to trigger to build the flutter app for Android, iOS and web.

## Installing some plugin into the Azure Pipeline for my azure project.

Find the plug in that you need and click on "Get it free" button.

![image](https://github.com/sk92129/AzurePipeline4Flutter/assets/1682772/2b56ad0d-dc58-4714-8fcf-c216eae9be90)

You need to be logged into your azure devops web site to see this after pressing the blue button.

![image](https://github.com/sk92129/AzurePipeline4Flutter/assets/1682772/9808e564-e55c-434e-bd04-13e21256c732)

Click the blue "install" button -- ensure you have the correct permission level.  Since this is a personal azure devops account, I have all the owner permission.

![image](https://github.com/sk92129/AzurePipeline4Flutter/assets/1682772/9e112057-9b7c-4f16-a314-97c5ca705499)

Install this on the azure pipeline for SonarQube code scanning.

https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarqube

![image](https://github.com/sk92129/AzurePipeline4Flutter/assets/1682772/ad57835f-e392-499b-a347-23de85db3cc0)

Click on Get It Free

It will download and install in the devops on the server and show this.

![image](https://github.com/sk92129/AzurePipeline4Flutter/assets/1682772/08c4f2be-ddc2-475f-8010-7cda0bbf4d2c)


When the sonar scan is done, a report is generated and can be viewed on the server where the sonar qube service is running from.
![Screenshot 2023-12-01 at 12-43-30 Kangster - Overview - SonarQube](https://github.com/sk92129/AzurePipeline4Flutter/assets/1682772/b0583a18-7e00-4602-ac01-0672eb08807e)



Using agent pool of a self-hosted centos machine to build on every trigger.
![image](https://github.com/sk92129/AzurePipeline4Flutter/assets/1682772/0c257870-ba1c-4d8f-9d0d-f87f45d6dfef)


## References

https://blogs.infosupport.com/flutter-sonarqube-with-azure-pipelines/

