# MedRemote-AWS
Utility application in Python that will keep track of AWS S3 buckets. 
You will be using the AWS Cloud9 IDE to develop this application. You will also use the AWS Python SDK Boto3 to enable your application to interact with AWS services. You then need to do the following in Cloud9:
Create a Cloud9 environment for this project
Make sure Python is installed on the Cloud9 server
Make sure pip is installed on the Cloud9 server
Install AWS SDK for Python (Boto3).
Instructions for these steps can be found at https://docs.aws.amazon.com/cloud9/latest/user-guide/sample-python.html. Make sure you update these instructions to match the version of Python you are running. For example, to install boto3 for Python 3.7, you would need to type the command:    sudo python3.7 -m pip install boto3.
Depending on the ownership of the AWS account you are using, you may need to set credentials to enable you to call S3 services. Check with your trainer/assessor if this is necessary.
To follow MedRemote standard practice, your application will be written in Python following the PEP-8 Style Guide. 


Pseudocode
Before you begin programming, you need to write the pseudocode for your application. There is no set style for the pseudocode, but it needs to be clearly written and appropriately formatted. If appropriate, break down the pseudocode into modules that will reflect the functions to be called.
Once written, you need to check the logic of your pseudocode carefully. You then need to submit it for review. Your trainer/assessor will advise on the process for this review (for example, there may be a peer review process where students review each other's pseudocode).  The results of this review will document the following: 
Names of the review participants
Date of review
Copy of pseudocode review
Issues identified
Fixes proposed
Participant sign-off.


Coding
Once approved, translate your pseudocode into Python using the Cloud9 environment you have created. 
At the start of your code, make sure you include any object libraries you will be using. 
The web page https://docs.aws.amazon.com/cloud9/latest/user-guide/sample-python.html contains some example code on manipulating S3 with Boto3, which you may find useful. A more detailed reference on using Boto3 with S3 can be found at https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/s3.html#id221
Make sure your code adheres to the standards you identified in Section 2.
As you write your script, you should continually and incrementally debug it in the Cloud9 environment to ensure that it works as expected.
Include code comments.
Section 4 – Test and Finalise scripts
Once you have written your script, you must thoroughly test that it correctly performs all the functions specified in the Requirements.
Write a brief test plan of the tests you will perform.
Create a document of these tests that includes screenshots from the Cloud9 console of the user inputs and the resultant outputs.  Confirm the results with screenshots from the S3 console showing buckets created and deleted.  Make and document any required changes to the code to ensure the code works as required.


