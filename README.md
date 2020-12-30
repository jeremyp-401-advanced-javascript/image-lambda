# LAB - Class 17

## Project: AWS Lambda - Create Thumbnail

### Author: Jeremy Penning

### Links and Resources

- [AWS Lambda Function ARN](arn:aws:lambda:us-west-2:219177530110:function:CreateThumbnail)

## How To Use

At the moment it seems that the only way to use this function is through CLI access reading a JSON file describing an image that has already been sent to S3, which isn't public. Hopefully there's a way to open up access.

## Issues with Deployment

I pretty much followed the Amazon tutorial (and used their code) to the letter. Inititally I ran into problems with the user I was trying to use to run the function, but was able to figure it out with a little help.

Everything else seemed to run pretty smooth. Here are my source and thumbnail images:

---

Photo Credit - Jeremy Penning

![thumbnail](./assets/resized-IMG_7988_sq.jpg)
![original](./assets/IMG_7988_sq.jpg)
