# AWS BUCKET ASSIGNMENT 
Create a static website and host it on S3 bucket(private bucket) but with public read policy assigned, using cloud front for CDN. 

# PROCEDURES FOR BUCKET CREATION
-. Log into your AWS account.
-. Search for S3 bucket.
-. Create a bucket making sure the bucket name is unique leave everyother option as default.
-. Click on the bucket and uplaod your desired file. I downloaded a zip file from HTML5up.net
-. If you downloaded a zip file make sure to extract before uploading.
-. Copyand move the downloaded files into the bucket root location.

# PROCEDURE FOR CLOUDFRONT CREATION
-.  Search for Cloudfront and create a new distribution.
-. Use bucket as origin name, Click on origin zsccess control.
-. Create new OAC
-. Enable security [rptection.
-. Documnent root object - index.html
-. Run

#CONCLUSION
- Copy policy and paste in S3 bucket permission (bucket policy) and save
- Go back to cloud front and copy the DNS assigned to the CloudFront.
- Run the domain and verify they run correctly.
