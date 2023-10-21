# serverless_architecture

### First assignment: Automated S3 Bucket Cleanup Using AWS Lambda and Boto3.
1. Created S3 bucket.
   ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/191e4509-9000-40a0-9b94-9a1ebb51a756)

2. Created lambda IAM role with all required accesses.
   ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/0c916848-0a83-4f55-b791-30616e20b697)

3. Created lambda function with python code to delete bucket older than 30 days.
   NOTE: I had bucket 20 days older so in code i have mentioned 20 instead of 30 days.
   ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/b1486658-7a20-4d8d-9a07-8f40c00a4fe5)
   ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/b9303b5f-e9d5-4665-bc17-4e0264bc6106)

4. Please find below screenshot in which bucket is not present now and find logs for same.
   ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/7990d0e3-2ca9-4cfc-9131-0924df3760db)
   ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/a1fb1cf9-b7b8-42f4-bb9a-a8f5623b04ef)

   





