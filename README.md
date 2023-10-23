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

 ### Second Assignment: Monitor EC2 Instance State Changes Using AWS Lambda, Boto3, and SNS.
 1. Created SNS. Please find below screenshot.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/8a2c2018-2918-4ae5-9992-d5ebdbd2a9ce)

 2. Created IAM role.
      ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/0c916848-0a83-4f55-b791-30616e20b697)

 3. Created Lambda function.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/83e8c371-251a-4339-85ee-3c65e23337a4)
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/daef940c-8239-42cc-bd42-4ce2f7baf122)

 5. Created trigger event bridge.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/48e9296c-03cd-4a74-891f-b846e6a1d3e1)

 6. Kindly find screenshot for SNS notification about the state change.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/e9db5ff2-5c67-45cc-943e-78666372d1d9)

 ### Third assignment: Load Balancer Health Checker.  
 1. Created a Lambda function. Kindly find below screenshot for same.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/074b352b-5fc0-49e7-b72b-e181786385ca)
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/b0eded74-cdcc-4fc9-a6c0-e0c857e593f0)

 2. Created ELB and target group. Kindly find below screenshot for same.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/4721b352-22a4-4229-9ac4-f3fbb92d4d2a)
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/dc680c58-c626-4d6a-871f-d8eefec1d46b)

 3. Kindly find below SNS notification for unhealthy instance.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/30642a43-f561-4b6e-a5c9-3db924b78455)

 4. Set up a CloudWatch event to trigger this Lambda function every 10 minutes.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/18fd8ab7-46b4-47b7-85e6-3a2abb586e9c)

 ### Sixth assignment: Auto-Tagging EC2 Instances on Launch Using AWS Lambda and Boto3. 
 1. Setup an EC2 instance.
 2. Created IAM role to access lambda.
 3. Created Lambda function. Kindlly find below screenshot.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/d0360ac8-7b5b-4dac-b189-3de003701007)
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/8e62c473-40e7-4b3e-9727-b4fbf9d97405)

 4. Created cloud watch event.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/3c922efd-c17d-44b6-806b-a3f7dfc60080)

 5. Tested whole setup successfully and EC2 instance tag is getting changed.
    ![image](https://github.com/himani0550/serverless_architecture/assets/77041503/432a106b-a052-4c1f-a85f-5f255cf15bd4)
  


  
   

   
   


    
   
   
    


   





