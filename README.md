# Deploy to Netlify
In this guide, you will learn how to deploy your tezjs site to Netlify.

## Deployed Url:
https://deluxe-bublanina-c01717.netlify.app/
https://chimerical-gelato-c61c52.netlify.app/ 

## Preparing for deployment:
Run the following command to create tezjs project:
  - `npm create tez@latest`
  - `cd [projectName]`
  - `npm install` - for installing the required dependencies
  - `npm run build` - for build the project
  - `npm run dev` - for run the project

## Pre-requisites
Make sure you have:
  - Netlify account.
  - node installed in your machine.

## Deployment
Go to https://www.netlify.com/ and login, create team. 
1. Deploy manually from created dist:   
    - Select add new site and choose deploy manually option from the sites page of Netlify team
    - Upload dist folder which contains index.html.

2. Import as existing project:
    - Select source control option from provided
    - Select repository 
    - Basic Build setings are like select build command `npm run build` and select publish directory as `dist\`
    - Select Deploy site

