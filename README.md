# Capstone Cloud Project

## Architecture
CloudFront → ALB → EC2 (Amazon Linux 2, t2.micro)

## AWS Resources
- EC2: Web-Server (t2.micro, eu-north-1)
- S3: capstone-s3-343073438650-us-east-1-an
- ALB: capstone-alb
- CloudFront: Distribution pointing to ALB

## Setup Guide
1. Clone this repository
2. Configure AWS CLI with capstone profile
3. Follow phase guides in /docs folder

## Team
- Aliu Tijani — AWS Console Admin
- Manu Adam Onyina — AWS Console Admin
- Freda Ofori — AWS Console Admin
- Caleb Ohene Asare — AWS Console Admin
