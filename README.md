# Agora React Demo

Quickstart for group video calls on React using Agora.io SDK. Use this guide to quickly start a multiple user group call.

# Prerequisites

- Node 14+
- A valid Agora account [Sign Up](https://dashboard.agora.io/en/) for free.

# Running this example project

## Generate an App ID

In the next step, you need to use the App ID of your project. Follow these steps to [Create an Agora project](https://docs.agora.io/en/Agora%20Platform/manage_projects?platform=All%20Platformshttps://docs.agora.io/en/Agora%20Platform/manage_projects?platform=All%20Platforms#create-a-new-project) in Console and get an [App ID](https://docs.agora.io/en/Agora%20Platform/terms?platform=All%20Platforms#a-nameappidaapp-id).

1. Go to [Console](https://dashboard.agora.io/) and click the [Project Management](https://dashboard.agora.io/projects) icon on the left navigation panel.
2. Click Create and follow the on-screen instructions to set the project name, choose an authentication mechanism (for this project select App ID without a certificate), and Click Submit.
3. On the Project Management page, find the App ID of your project.
4. Check the end of document if you want to use App ID with the certificate.

## Steps to run our example

1. Download and extract the zip file.
2. Run `npm install` or use `yarn` to install the app dependencies in the unzipped directory.
3. Navigate to ./src/App.js and enter your App ID that we generated as appId: YourAppId,
4. Open a terminal and execute `npm start`

## Sources

- Agora [API Doc](https://docs.agora.io/en/)
- [Issues feedback](https://github.com/AgoraIO-Community/Agora-RN-Quickstart/issues)
- [React](https://reactjs.org/)
