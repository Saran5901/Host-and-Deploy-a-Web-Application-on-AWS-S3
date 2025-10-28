# Host-and-Deploy-a-Web-Application-on-AWS-S3
AWS S3 Static Website Hosting.

Tools Used
- Amazon Web Services (AWS) – S3 service.
- VS Code – to create HTML file.
- Web Browser – to test the hosted site.

I created a simple HTML web app and deployed it using AWS S3 Static Website Hosting.
I created a public bucket, uploaded my files, enabled website hosting, and accessed it through the provided endpoint URL.

Step-by-Step Process
1️) Create a Simple Web Page:
   - Created a basic index.html file. 
2️) Create an S3 Bucket :
   - Logged in to AWS Console → S3.
   - Clicked Create Bucket.
   - Gave a unique name and region.

3️) Upload Files :
   - Opened the bucket → Upload → Add files → index.html.
   - Clicked Upload.

4️) Enable Static Website Hosting :
   - Go to Properties → Static website hosting → Edit.
   - Selected Enable.
   - Entered index.html as the index document.
   - Clicked Save changes.
   - Copied the Website endpoint URL.

5️) Make the Website Public :
   - Opened Permissions → Edit Block public access → unchecked all → Save
   - Added a Bucket Policy

6️) Test the Website :
   - Opened the endpoint URL in a browser :
       https://saranawscloudapp123.s3.ap-south-1.amazonaws.com/index.html
   - The web page displayed successfully.
