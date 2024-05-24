# Full-Stack Notes Application with AWS Backend Setup

A simple full-stack notes application built with React.js for the frontend and AWS Amplify for the backend. This application allows users to create and delete notes, and it leverages various AWS services, including AWS Cognito for authentication, AWS AppSync for the GraphQL API, Amazon DynamoDB for database storage, and Amazon S3 for storing images.

## User Interface
<img src="/assets/images/auth.png" width="400" height="200"> <img src="/assets/images/ui.png" width="400" height="200">

## Features and Technologies used

- User authentication with AWS Cognito.

- Create and delete notes.

- Use of GraphQL API for data interactions.

- Storage of images in Amazon S3.

- Backend storage and retrieval of notes in Amazon DynamoDB.

## Prerequisites

Before you can use this application, ensure you have the following prerequisites:

- Node.js and npm installed.
- An AWS account with Amplify, Cognito, and AppSync services configured.
- Git and GitHub account (for hosting the frontend).

## Setup

1. Clone this repository (if you haven't already):

   ```bash
   git clone https://github.com/yashsharma127/aws-amplify-fullstack.git
   cd aws-amplify-fullstack
   ```

2. Install the required dependencies:

   ```bash
   npm install
   ```

3. Configure the AWS Amplify CLI to connect to your AWS account:

   ```bash
   amplify configure
   ```

4. Deploy the backend services using Amplify:

   ```
   amplify push
   ```

5. Deploy the frontend using Amplify:

   ```
   aamplify add hosting
   amplify publish
   ```

## AWS successful deployment
<img src="/assets/images/frntdep.png" width="400" height="200"> <img src="/assets/images/bakdep.png" width="400" height="200">

## Usage

1. You can access hosted application from your aws amplify dashboard.

2. You can access it locally:

   ```
   npm start
   ```

## Cleaning Up

To stop and remove whole project from aws:

```
amplify delete
```
