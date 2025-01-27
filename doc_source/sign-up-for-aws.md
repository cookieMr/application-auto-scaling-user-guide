# Sign up for an AWS account<a name="sign-up-for-aws"></a>

When you sign up for an account with Amazon Web Services, your account is automatically signed up for all Amazon Web Services, including Application Auto Scaling\. You are charged only for the services that you use\. 

If you don't already have an AWS account, you need to create one\. If you already have an AWS account, you can skip the steps for creating an account in the following procedure and move to creating an IAM user in step 3\.<a name="set-up-aws-account"></a>

**To sign up for an AWS account**

1. Open [https://aws\.amazon\.com/](https://aws.amazon.com/) and choose **Sign Up**\.

1. Follow the online instructions\. Part of the sign\-up procedure involves receiving a phone call and entering a verification code on the phone keypad\. AWS sends you a confirmation email after the sign\-up process is complete\.

1. Create an AWS Identity and Access Management \(IAM\) admin user\. See [Creating your first IAM user and group](https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html) in the *IAM User Guide* for instructions\. 
**Important**  
The getting started exercises in this guide assume that you have a user \(`adminuser`\) with administrator permissions\. Follow the procedure to create `adminuser` in your account\.

1. Make sure that you have an access key ID and a secret access key associated with the IAM user that you just created\. For more information, see [Access key and secret access key](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html#cli-quick-configuration-creds) in the *AWS Command Line Interface User Guide*\.

For more information about IAM, see the following:
+ [AWS Identity and Access Management \(IAM\)](https://aws.amazon.com/iam/)
+ [Getting started](https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started.html)
+ [IAM User Guide](https://docs.aws.amazon.com/IAM/latest/UserGuide/)

**Using Application Auto Scaling in AWS Regions**  
Application Auto Scaling is available in multiple AWS Regions\. For a list of available Regions, see the [Regions and endpoints](https://docs.aws.amazon.com/general/latest/gr/as-app.html) table in the *AWS General Reference*\. A global AWS account allows you to work with resources in most Regions\. When using Application Auto Scaling with resources in the China Regions, keep in mind that you must have a separate Amazon Web Services \(China\) account\. In addition, there are some differences in how Application Auto Scaling is implemented\. For more information on using Application Auto Scaling in the China Regions, see [Application Auto Scaling in China](https://docs.amazonaws.cn/en_us/aws/latest/userguide/application-auto-scaling.html)\.