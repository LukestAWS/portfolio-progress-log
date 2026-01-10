# LukestAWS Portfolio Progress Log
Live Portfolio Site: https://lukestaws.github.io
Future Consultancy Site: aws4less.co.uk (Week 3 migrate)

## Current Status (Updated 10 Jan 2026)
- Week 1–2: URL Shortener → FastAPI + Postgres + Redis caching + GitHub Actions CI/CD + **PUBLIC LIVE** on Fly.io[](https://aws-url-shortener.fly.dev)
- Week 3–4: LaunchList SaaS → CDK Python IaC + S3+CloudFront static frontend live + DynamoDB single-table + Lambda + API Gateway backend + Cognito auth + protected /subscribe endpoint
- Full stack deployed: https://d1psz3m8fwuyiu.cloudfront.net (frontend) + https://26omys58w7.execute-api.us-east-1.amazonaws.com/prod/subscribe (API)
- Cognito User Pool + App Client live (self-sign-up + auto-verify email)
- Portfolio site updated: hero text + progress badge ("Projects live: 2/4") + LaunchList card with live URL + screenshot
- Cantrill Progress: Docker 100%, CDK Fundamentals/Deep Dive via workshop + official docs (equivalent)

## Achievements (Milestones Shipped)
- **15 Dec 2025**: URL Shortener public deploy LIVE on Fly.io + healthy endpoint + Swagger docs
- **17 Dec 2025**: Redis caching LIVE on public deploy (Upstash) – "cached": true proven
- **19 Dec 2025**: First CDK stack deployed – S3+CloudFront static site live
- **29 Dec 2025**: LaunchList static frontend live on CloudFront (Coming Soon page)
- **5 Jan 2026**: LaunchList backend live – DynamoDB + Lambda subscribe + API GW
- **6 Jan 2026**: Cognito auth + protected API endpoint (single POST /subscribe)
- **10 Jan 2026**: Portfolio site hero + progress badge + LaunchList card with live demo + screenshot

## Weekly Check-Ins
- Week 1–2 (12–25 Dec): URL Shortener complete – public + Redis + CI/CD **[COMPLETE]**
- Week 3–4 (29 Dec – 10 Jan): LaunchList SaaS – static frontend + full backend + Cognito auth **[COMPLETE]** (SES emails + React form next)
- Week 5 (11–17 Jan): Polish Week – architecture diagram + cost breakdown + dev.to article + 10-min video

## Quick Notes / Blockers
- Everything within free tier – CloudFront 1TB free, S3 negligible, API Gateway/Lambda/DynamoDB pay-per-request
- No blockers – momentum back, Boss Day tomorrow (full polish + job apps prep)

Updated every Thursday Boss Day or when big progress hits.
