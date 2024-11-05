# AWS-Simple-Website
Simple website hosted on AWS that connects to Stripe.

## Problem
A friend had recorded an audio file they wanted to share with others, but also receive payment in the form of donations.

## AWS Solution Architecture
I designed a very simple architecture for a website where people can donate money in order to receive access to the audio file.

The architecture uses CloudFront to encrypt data with HTTPS, which is important to make users feel more safe using a website they might buy a product from.
The website HTML, CSS, and audio files are hosted on an S3 Bucket website endpoint.

![AWS Architecture Diagram for Website](https://github.com/user-attachments/assets/972de909-9550-4964-b4a4-8e3a7c4e5955)

## URL
https://d26u9dbf28sbcq.cloudfront.net

## Next Steps
If I had a registered domain, I would use Route 53 to setup a host zone, configure DNS, and connect the registred domain so that the URL would be more human-readable.
