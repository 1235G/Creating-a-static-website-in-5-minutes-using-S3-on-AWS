# Creating-a-static-website-in using-S3-on-AWS

Cloud platform: AWS • Tools used: Atom (Text editor), S3 (AWS) • Languages: Html


Steps
1. Create a bucket on S3 named pythondatastructure


3. Change the number since you must have a unique bucket name on S3) 
5. Create three files, index.html, error.html, about.html
6. Upload the files in the S3 bucket

 


Step 1: Creating Bucket in S3:
![image](https://user-images.githubusercontent.com/88941914/158775062-86ed2174-7af7-4500-a7c5-8ebd16dfbc9b.png)

Step 2: Enter the Bucket name. Note that the Bucket name should be unique. Add something at the end to get a unique Bucket name.
![002](https://user-images.githubusercontent.com/88941914/158775515-a940bd66-b51e-406a-b28c-88ab195fe372.png)

Step 3: Giving the public permissions to the S3 Bucket.Any folder/file in the Bucket would only be visible to the owner who created it. For a website, the Bucket should be given public access for the rest of the world to access it as a webpage. Click on the Properties tab, make sure the “Block public access” is selected and click on the Edit button.
![004](https://user-images.githubusercontent.com/88941914/158776269-82c5b90f-77d7-43ed-9817-9863e459491c.png)

Step 3: Now is the time to make the Bucket public. Click on the “Bucket Policy” and enter the below policy, make sure to change the Bucket name to what was created in Step 1. Click on Save to make the Bucket public

![007](https://user-images.githubusercontent.com/88941914/158776712-cbabe67f-d13d-428c-a6d3-293d04662b17.png)

Step 4: Enabling Static website hosting and uploading the website to S3.
Now is the time to enable “Static website hosting” for S3. Notice that by default, it is disabled. Click on the card and select “Use this Bucket to host a website”.
![009](https://user-images.githubusercontent.com/88941914/158777152-4419e914-3500-4daa-a27e-3cc1fdecde04.png)
![010](https://user-images.githubusercontent.com/88941914/158777362-8c001a72-8315-49e1-a3b5-fc8831705fef.png)

step5: uploding html page in aws.
![015](https://user-images.githubusercontent.com/88941914/158777537-9565237f-1c50-4134-a2b2-6ceedca500b8.png)

Step 6: Access the webpage hosted in S3
http://pythondatastructureaws55.s3-website.ap-south-1.amazonaws.com/
