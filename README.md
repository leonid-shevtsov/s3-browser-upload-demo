# Minimal demo of S3 browser upload 

This is a supplement to the [Demystifying S3 browser upload](http://leonid.shevtsov.me/en/demystifying-s3-browser-upload) article.

## How to run

You will need [Node.js](https://nodejs.org).

Get an AWS account, create an S3 bucket, generate a key pair (refer to the article for details), then run:


``` shell
env S3_ACCESS_KEY=xxx S3_SECRET_KEY=xxx S3_BUCKET=xxx S3_REGION=xxx node server.js
```

and finally open [http://localhost:5000](http://localhost:5000) in your browser.
