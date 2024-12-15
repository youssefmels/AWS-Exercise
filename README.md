# AWS-Exercise

Found this on reddit https://www.reddit.com/r/dataengineering/comments/zy8lrb/aws/?rdt=45580

Credit to u/pro__acct__ for this comment

Do the following using the boto3 package:

   - Write a csv file to s3 and read a csv from s3. This’ll get you comfortable with using boto3 clients
   
   - Create a Lambda that moves the file from one prefix in s3 to another prefix in s3 and test that it works

Do the following manually:

   - Create and delete an ec2 instance. Create one again and resize it. Try and automate creation using a “Launch Template”
   
   - create a Aurora Serverless V2 RDS database instance

   - connect to this instance using a database client
   
   - write a job using Glue Studio that takes the csv file from s3 and writes it to a table in the RDS instance
   
   - Create a Glue database and a Glue crawler and crawl the csv in S3 to add it to the Glue Database
   
   - Query the Glue Database in Athena
   
   - Query the RDS instance using Python from the EC2 instance
   
   Bonus - CloudFormation:
   
   - Launch an S3 Bucket using a CloudFormation Template
   
Figure out how to do the above and you’ll be in good AWS noob Data Engineer shape. There’s plenty more tho this is a good start
