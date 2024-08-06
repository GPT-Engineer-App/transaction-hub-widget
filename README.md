# Welcome to your GPT Engineer project

## Project info

**Project**: transaction-hub-widget 

**URL**: https://run.gptengineer.app/projects/d96e83db-50cd-4315-9923-5e67f51cad25/improve

**Description**: create Create an application that has the following sections; 1. Mariadb database 2. Express Js backend 3. API endpoints 4. ReactJs User Interface On the application create the following features and the corresponding segments. 1. Create the default super user access username and password to be used for access the first time. 2. Create a login page that users input their username and password to access the application. 3. Create the landing page where users get redirected after successful login. 4. Create the profile section where the logged in user can edit their profile, change their password, update their details and logout. 5. Create a navigation bar on the landing page which holds access to other modules within the application. 6. Create login session which exits by logging out if left for 30 minutes. 7. Create an app module that allows admin user to login and initiate transfer request. 8. Create a notification icon on the top right of the navigation bar where the logged in user gets the notification. 9. Create an 'initiate transfer request' feature where the logged in executive user uses to post an initiated transaction request by submitting a form with the name of the sender, email, residential address, mobile number, recipient's name, recipient's address, amount to be sent, currency and nationality. 10. Create a feature that allows all employee users to get the notification of the initiated transaction request. 11. Create the feature that updates the status of initiated transaction request from unread to read and sends the notification update to the executive user. 12. Create a feature that allows the employee user to process initiated transaction by updating the 'delivery' by inputting the recipient's name, transaction code, transaction date, transaction amount and transaction notes. Create a reporting feature and the step by step procedure on how to setup the codebase and run the application. create the structure of the project and the necessary files to implement the features statedan admin panel with secure authentication 

## Who is the owner of this repository?
By default, GPT Engineer projects are created with public GitHub repositories.

However, you can easily transfer the repository to your own GitHub account by navigating to your [GPT Engineer project](https://run.gptengineer.app/projects/d96e83db-50cd-4315-9923-5e67f51cad25/improve) and selecting Settings -> GitHub. 

## How can I edit this code?
There are several ways of editing your application.

**Use GPT Engineer**

Simply visit the GPT Engineer project at [GPT Engineer](https://run.gptengineer.app/projects/d96e83db-50cd-4315-9923-5e67f51cad25/improve) and start prompting.

Changes made via gptengineer.app will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in the GPT Engineer UI.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps: 

```sh
git clone https://github.com/GPT-Engineer-App/transaction-hub-widget.git
cd transaction-hub-widget
npm i

# This will run a dev server with auto reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with .

- Vite
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

All GPT Engineer projects can be deployed directly via the GPT Engineer app. 

Simply visit your project at [GPT Engineer](https://run.gptengineer.app/projects/d96e83db-50cd-4315-9923-5e67f51cad25/improve) and click on Share -> Publish.

## I want to use a custom domain - is that possible?

We don't support custom domains (yet). If you want to deploy your project under your own domain, then we recommend GitHub Pages.

To use GitHub Pages you will need to follow these steps: 
- Deploy your project using GitHub Pages - instructions [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site#creating-your-site)
- Configure a custom domain for your GitHub Pages site - instructions [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)