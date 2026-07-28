# Deploy a Static Website on AWS

## Project Overview
This project demonstrates how to deploy a static website on Amazon Web Services (AWS) using Amazon S3 for storage and CloudFront for content delivery. The website consists of simple HTML, CSS, and JavaScript files, making it ideal for S3 hosting without the need for a server.

The deployment process includes creating an S3 bucket, uploading website files, configuring public access, enabling static website hosting, and setting up CloudFront for faster and more reliable delivery.

## Project Objective
The main goal of this project is to:
- Host a static website on AWS
- Make the website publicly accessible
- Improve delivery performance using CloudFront
- Understand the basic workflow of AWS storage and CDN services

## Files in the Project
- index.html - The main homepage of the website
- css/ - Stylesheets used to design the website
- img/ - Image assets used by the site
- vendor/ - Bootstrap, Font Awesome, and JavaScript libraries required for the website

## Steps Used for Deployment
1. Create an S3 bucket
   - Create a new S3 bucket in the AWS Management Console.
   - Uncheck the option for blocking all public access.

2. Upload website files
   - Upload the project files and folders from your local machine to the S3 bucket.

3. Set the bucket policy
   - Configure the bucket policy to allow public read access.

4. Enable static website hosting
   - Open the bucket properties and enable the static website hosting feature.
   - Set index.html as the default index document.

5. Create a CloudFront distribution
   - Use the S3 bucket as the origin domain.
   - Configure CloudFront to distribute the website content globally.

6. Access the website
   - Open the S3 endpoint or CloudFront URL in a browser.
   - If needed, append /index.html to the URL.

## Screenshots
Below are the key screenshots from this project:

![S3 Bucket Creation](bucket.png)

![Bucket Policy Configuration](bucketPolicy.png)

![Static Website Hosting Setup](S3_bucket_static_web_hosting.png)

![Website Objects Uploaded to S3](objects.png)

![CloudFront Distribution Setup](cloudfrontDistribution.png)

![Website Preview](website.png)

## Result
This project successfully demonstrates how to host a static website on AWS using S3 and CloudFront. The website becomes publicly accessible and benefits from improved content delivery performance.

## Notes
- S3 is ideal for static websites because it does not require server-side processing.
- CloudFront helps reduce latency and improves global access speed.
- Proper bucket policies and permissions are essential for secure public hosting.

## Author
Pushpam Kumar
