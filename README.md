
# Project Name:  ECommerce-Website hosting with AWS S3 and CloudFront

## Overview:
This project demonstrates the setup and configuration of Amazon S3 (Simple Storage Service) and CloudFront to host and deliver a sample "ECommerce_Website". By leveraging these AWS services together, we ensure efficient and secure hosting while enhancing performance and user experience with low latency.
![CloudFront_Static_Website_hosting](https://github.com/RajPractiseRepo/AWS_CloudFront_ECommerce_website_/assets/148358152/3d66a5ea-ce9d-4ec2-a044-ec35499c0862)

![ecommerce_website](https://github.com/RajPractiseRepo/AWS_CloudFront_ECommerce_website_/assets/148358152/b62e6b1a-153e-491f-b150-2ce767fb9a74)


## Requirements:
- An AWS account
- Basic familiarity with AWS services (S3, CloudFront)
- A Sample Index.html page 

## Steps:
1. **Create an S3 Bucket:**
   - Create a new S3 bucket to store the sample Index.html page.

2. **Access Initial Issues:**
   - Attempt to access the EComerce Website directly through its S3 object URL. Encounter restrictions due to the initial bucket policy as blocked All public access.

3. **Set up CloudFront Distribution:**
   - Create a CloudFront distribution specifically for the Static page.
   - Configure essential options such as origin settings, caching behavior, and distribution settings.

4. **Update Bucket Policy:**
   - Update the bucket policy to allow access of static website via CloudFront. Ensure proper permissions are set.

5. **Test Setup:**
   - Copy and paste the CloudFront distribution domain name and any required query parameters or object keys into a web browser.
   - Verify that the Static website is accessible without encountering previous permission-related obstacles.

6. **Finalize Configuration:**
   - Adjust CloudFront settings as necessary for optimal performance and security.
   - Ensure proper monitoring and logging are enabled for the CloudFront distribution.
