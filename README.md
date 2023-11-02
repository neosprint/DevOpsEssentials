# DevOpsEssentials
Few Notes and Comments by Sumit


****S3Bucket Public hosting Policy ****

{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::bucketname/*"
        }
    ]
}

**Cloudfront Invalidate using Lambda Functions**

https://medium.com/fullstackai/aws-creating-a-cloudfront-invalidation-in-codepipeline-using-lambda-actions-49c1fd3a3c31

{"distributionId": "string", "objectPaths": ["/*"]}


