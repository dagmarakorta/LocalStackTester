# 🧪 LocalStackTester

An experimental C# console app meant as a **sandbox for playing with LocalStack** and testing different AWS SDK features locally.

The goal is to quickly try out AWS services (like S3, SNS, SQS, etc.) using the .NET SDK — without deploying anything to the actual cloud ☁️

## 📦 What's in here (so far)

- A minimal `.NET` console project: `LocalStackTester`
- Early draft of a function that asks for an S3 bucket name and prints a message
- An empty `docker-compose.yml` file — planning to use it to run LocalStack containers

## 🛠 Requirements

- [.NET SDK 8+](https://dotnet.microsoft.com/)
- [Docker](https://www.docker.com/) + [Docker Compose](https://docs.docker.com/compose/)
- (Optional) [LocalStack CLI](https://docs.localstack.cloud/getting-started/)

## 🚀 Running the project (basic for now)

```bash
dotnet run --project LocalStackTester
```

It will prompt for a bucket name and display a message — nothing functional yet. Just warming up :)

## 🧭 Roadmap / Ideas

- [ ] Fill in `docker-compose.yml` to spin up LocalStack with S3, SNS, SQS, etc.
- [ ] Connect AWS SDK to LocalStack endpoints
- [ ] Add logic to create buckets, upload files, and test other services
- [ ] Explore SNS → SQS flow locally
- [ ] Maybe play with Lambda or Step Functions later

## 📝 Notes

This repo is a playground — not meant for production use.  
The purpose is learning, testing, and having fun with AWS locally 🛠
