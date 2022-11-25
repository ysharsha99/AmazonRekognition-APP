# AmazonRekognition-APP
Mini project  AWS face recognition app
AWS Services Used
Amazon EC2 - Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. Amazon EC2’s simple web service interface allows you to obtain and configure capacity with minimal friction. It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment. Amazon EC2 offers the broadest and deepest compute platform with choice of processor, storage, networking, operating system, and purchase model. We offer the fastest processors in the cloud and we are the only cloud with 400 Gbps ethernet networking. We have the most powerful GPU instances for machine learning training and graphics workloads, as well as the lowest cost-per-inference instances in the cloud.
Amazon Rekognition - Amazon Rekognition makes it easy to add image and video analysis to your applications using proven, highly scalable, deep learning technology that requires no machine learning expertise to use. With Amazon Rekognition, you can identify objects, people, text, scenes, and activities in images and videos, as well as detect any inappropriate content. Amazon Rekognition also provides highly accurate facial analysis and facial search capabilities that you can use to detect, analyze, and compare faces for a wide variety of user verification, people counting, and public safety use cases.
Amazon VPC - Amazon Virtual Private Cloud (Amazon VPC) is a service that lets you launch AWS resources in a logically isolated virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways. You can use both IPv4 and IPv6 for most resources in your virtual private cloud, helping to ensure secure and easy access to resources and applications.
AWS Identity and Access Management (IAM) - AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources. IAM is a feature of your AWS account offered at no additional charge. You will be charged only for use of other AWS services.

Resources Used:
index.html: Markup for the static application
https://awsmc-dd.s3.ap-south-1.amazonaws.com/index.html
index.js: Javascript logic for making API calls to the backend
https://awsmc-dd.s3.ap-south-1.amazonaws.com/index.js
server.js: Backend logic which invokes the Amazon Rekognition service on the user’s behalf
https://awsmc-dd.s3.ap-south-1.amazonaws.com/server.js
package.json: Dependency list for server.js
https://awsmc-dd.s3.ap-south-1.amazonaws.com/package.json
Frameworks/Libraries Used
Bootstrap v5 
Bootstrap is a free and open-source framework for building the front end of the application.
Learn More: https://getbootstrap.com/
aws-sdk v2 for Javascript
aws-sdk allows our application to access the AWS services on our behalf.
Example: Listing all the buckets in our S3 account
Learn More: https://docs.aws.amazon.com/sdk-for-javascript
