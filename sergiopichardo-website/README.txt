Deploy Static Website on AWS

In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.



The files included are: 

index.html - The Index document for the website.
/img/beach.jpg - The background image file for the website.
/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
/css - CSS files for the website.



URLs 

CloudFront URL: 
http://d3tkzpmbbjnkun.cloudfront.net/index.html

S3 bucket URL: 
https://sergiopichardo-udacity-website.s3.amazonaws.com/index.html



Other 

- I enabled S3 Versioning because I had to change some text and the background image 
and I thought it would help when I uploaded changes. 
- I also had to invalidate some paths in my cloudfront distribution 
because the changes on the s3 bucket were not propagating due cloudfront caching. 
- I had so much fun doing this. Thank you udacity team!




